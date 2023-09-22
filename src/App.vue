<script setup>
import Navbar from './components/Navbar.vue';
import Introduction from './components/Introduction.vue';
import Projects from './components/Projects.vue';

</script>
<!-- portfolio -->
<template>
    <Navbar />
    <main>
        <Introduction id="home" />
        <!-- <Projects id="projects" /> -->
        <!-- <Technologies id="technologies" /> -->
        <!-- <Skills id="skills" /> -->
        <Projects id="projects"/>
    </main>
</template>
