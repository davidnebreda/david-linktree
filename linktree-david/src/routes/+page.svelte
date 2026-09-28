<div id="home_page" class="page">
    <div id="grid_header" class="grid grid_styles">
        <div class="cell">
            <MainMenu />
        </div>
    </div>
    <div id="grid_section_blog" class="grid grid_styles">
      <div class="cell">
        <SectionBlog />
      </div>
    </div>
</div>

<script lang="ts">
    import MainMenu from '../components/mainmenu.svelte';
    import SectionBlog from '../components/sectionblog.svelte';
</script>

<style>
    #home_page
    {
        width: 100%;
    }

    .grid_styles
    {
        width: 85%;
    }

    
</style>