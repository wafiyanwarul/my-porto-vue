<template>
  <div id="app">
    <AboutMe />
    <Education />
    <OrganizationExperiences />
    <WorkExperiences />
    <Skills />
    <Projects />
    <ContactMe />
    <TechMerch />
  </div>
</template>

<script>
import AboutMe from './components/AboutMe.vue';
import Education from './components/EducationSection.vue';
import OrganizationExperiences from './components/OrganizationExperiences.vue';
import WorkExperiences from './components/WorkExperiences.vue';
import Skills from './components/SkillsSection.vue';
import Projects from './components/ProjectsSection.vue';
import ContactMe from './components/ContactMe.vue';
import TechMerch from './components/TechMerch.vue';

export default {
  name: 'App',
  components: {
    AboutMe,
    Education,
    OrganizationExperiences,
    WorkExperiences,
    Skills,
    Projects,
    ContactMe,
    TechMerch
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
