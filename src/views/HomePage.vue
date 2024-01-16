<template>
  <div class="container">
    <HeaderBlock />
    <AlwaysBlock />
    <ProjectBlock/>
    <CodeBlock/>
    <DesignBlock/>
    <DeveloperBlock/>
    <LogoBlock/>
    <StartedBlock/>
    <FooterBlock/>
    <TestBlock/>
  
  </div>
</template>

<script>
import HeaderBlock from "@/components/HeaderBlock/HeaderBlock.vue";
import AlwaysBlock from "@/components/AlwaysBlock/AlwaysBlock.vue";
import ProjectBlock from "@/components/ProjectBlock/ProjectBlock.vue";
import CodeBlock from "@/components/CodeBlock/CodeBlock.vue";
import DesignBlock from "@/components/DesignBlock/DesignBlock.vue";
import DeveloperBlock from "@/components/DeveloperBlock/DeveloperBlock.vue";
import LogoBlock from "@/components/LogoBlock/LogoBlock.vue";
import StartedBlock from "@/components/StartedBlock/StartedBlock.vue";
import FooterBlock from "@/components/FooterBlock/FooterBlock.vue";
import TestBlock  from "@/components/TestBlock/TestBlock.vue";
 


export default {
  name: "HomePage",
  data() {
    return {
      isChecked: false,
    };
  },
  methods: {},
  components: { HeaderBlock, AlwaysBlock,ProjectBlock,CodeBlock,DesignBlock,DeveloperBlock,LogoBlock,StartedBlock,FooterBlock,TestBlock }
};
</script>
