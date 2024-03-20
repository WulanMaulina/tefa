<script setup>
const supabase = useSupabaseClient()

const route = useRoute()
const buku = ref([])

const getBooksById = async () => {
    const { data, error } = await supabase.from('buku').select(`*, kategori(*)`)
    .eq('id', route.params.id)
    if(data) buku.value = data[0]
}

onMounted(() => {
    getBooksById
})

<h2 class="text-start my-4">{{ buku.judul }}</h2>
</script>
