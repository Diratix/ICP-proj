<template>
  <Header />
  <Box nameBox="About Me" contentBox="Currently, I am a fifth-grade student at the Technical and IT School Complex in Busko Zdrój, majoring in IT technician. I can create, manage and administer networks, solve problems related to Windows and Linux operating systems, administer servers based on Linux and Windows Server, is great at virtualization operating systems and configuration of NetGear and MicroTik devices. I can create scri"/>
  <Box nameBox="Experience" contentBox="I completed my education at Zespół Szkół techniczno-Informatycznych in Busko-Zdrój, specializing in INF-2 with a focus on IT. During my internship at BajtNet sp z o.o., I worked on network administration, including configuring and maintaining network hardware, setting up routers and switches, and installing structured cabling for office spaces. At V-Art Escuela de Animación 3D y Audiovisual in Sevilla, I was involved in planning, designing, and developing mobile applications using Java in Android Studio. I contributed to creating user interfaces, optimizing app performance, and troubleshooting bugs to improve functionality."/>
  <Tags nameBox="Projects" />
</template>

<script>
import Header from './components/header.vue';
import Box from './components/box.vue';
import Tags from './components/tags.vue';
export default {
  name: "App",
  components: {
    Header,
    Box,
    Tags,
  },
};
</script>