<template>
    <div id="main-menu">
        <menu-bar/>
        <panel-menu/>
    </div>
</template>

<script>
import MenuBar from './MenuBar.vue'
import PanelMenu from './PanelMenu.vue'

export default {
  name: 'MainMenu',
  components: {
    MenuBar,
    PanelMenu
  }
}
</script>