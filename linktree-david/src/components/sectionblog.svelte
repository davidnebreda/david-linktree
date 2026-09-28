<section id="blog" class="section">
    <figure class="image is-64x64">
       <img src={WpLogo} alt="Wordpress Logo" width="100%" height="100%" />
    </figure>
    <h2 class="is-size-2-desktop is-size-3-touch has-text-centered has-text-weight-bold has-text-light mx-3">
        Blog
    </h2>
</section>

<script lang="ts">
    import WpLogo from '../assets/images/wp.png';
</script>

<style>
    #blog
    {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        flex:1;
        width: 100%;
        gap:6;
    }
</style>