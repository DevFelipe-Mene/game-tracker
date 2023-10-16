<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #image>
      <DocumentationIcon />
    </template>
    <template #name>Documentation</template>
  </WelcomeItem>

  <WelcomeItem>
    <template #image>
      <ToolingIcon />
    </template>
    <template #name>Tooling</template>

  </WelcomeItem>

  <WelcomeItem>
    <template #image>
      <EcosystemIcon />
    </template>
    <template #name>Ecosystem</template>

  </WelcomeItem>

  <WelcomeItem>
    <template #image>
      <CommunityIcon />
    </template>
    <template #name>Community</template>

  </WelcomeItem>

  <WelcomeItem>
    <template #image>
      <SupportIcon />
    </template>
    <template #name>Support Vue</template>
    
  </WelcomeItem>
</template>
