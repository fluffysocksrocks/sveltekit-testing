<script>
    import { page } from '$app/state'
</script>

<style>
    * {
        color: red;
    }
</style>

<h1>{page.status}</h1>
<p>{page.error?.message} ... :&lpar; this is very sad</p>