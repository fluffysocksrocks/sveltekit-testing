<script>
    import { page } from '$app/state'
</script>

<style>
    p {
        color: red;
    }
</style>

<h1>{ page.status }</h1>
<p>{ page.error?.message }</p>
<p>:&lpar; this is very sad</p>