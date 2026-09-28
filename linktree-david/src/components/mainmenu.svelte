<header id="main_header">
    <MainHero />
    <nav id="main_header_nav" class="is-block w-100">
       <ul id="main_header_nav_items">
          <li><a href="#blog" target="_self" title="Artículos del Blog de David" aria-label="Artículos del Blog de David" class="has-text-light has-text-weight-bold main_header_nav_item">Blog</a></li>
          <li><a href="#social" target="_self" title="Artículos del Blog de David" aria-label="Artículos del Blog de David" class="has-text-light has-text-weight-bold main_header_nav_item">Social Media</a></li>
          <li><a href="#projects" target="_self" title="Artículos del Blog de David" aria-label="Artículos del Blog de David" class="has-text-light has-text-weight-bold main_header_nav_item">Proyectos</a></li>
          <li><a href="#podcast" target="_self" title="Artículos del Blog de David" aria-label="Artículos del Blog de David" class="has-text-light has-text-weight-bold main_header_nav_item">Podcast</a></li>
       </ul>
    </nav>
</header>

<style>
    #main_header
    {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 100%;
    }
    
    #main_header_nav
    {
        background-color: #388e3c;
        
    }

    #main_header_nav_items
    {
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
        padding-left: 10px;
        padding-right: 10px;
        gap: 4rem;
    }

    .main_header_nav_item
    {
        font-size: 1.2rem;
    }
</style>

<script lang="ts">
    import MainHero from "./mainhero.svelte";
</script>