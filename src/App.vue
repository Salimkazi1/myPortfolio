<template>
    <div>
    <HeaderComponent v-bind:websiteName="websiteName"></HeaderComponent>
    <SelfIntroComponent></SelfIntroComponent>
    
      <div class="row align-items-md-stretch">
          <div class="col-md-6">
              <NewsletterComponent></NewsletterComponent>
          </div>

          <div class="col-md-6">
              <SkillsComponent></SkillsComponent>
          </div>
      </div>
    <FooterComponent></FooterComponent>
    <ProjectComponent></ProjectComponent>
    <ProjectListComponent></ProjectListComponent>
    
    </div>  
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import SelfIntroComponent from './components/SelfIntroComponent.vue';
import NewsletterComponent from './components/NewsletterComponent.vue';
import SkillsComponent from './components/SkillsComponent.vue'; 
import FooterComponent from './components/FooterComponent.vue';
import ProjectComponent from './components/ProjectComponent.vue';
import ProjectListComponent from './components/ProjectListComponent';


export default {
    data() {
      return {
        websiteName: 'My Portfolio'
      }
    },
    components: { HeaderComponent, SelfIntroComponent, 
    NewsletterComponent, SkillsComponent, FooterComponent, 
    ProjectComponent, ProjectListComponent}
}
</script>



<style>

</style>