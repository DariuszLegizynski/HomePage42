<template>
  <Header />
  <ContactForm />
  <HeroSection />
  <Projects />
  <TrustedUs />
  <Credentials />
  <Process />
  <Footer />
</template>

<script>
import Header from './components/Header.vue'
import ContactForm from './components/ContactForm'
import HeroSection from './components/HeroSection'
import TrustedUs from './components/TrustedUs'
import Projects from './components/Projects'
import Credentials from './components/Credentials'
import Process from './components/Process'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    ContactForm,
    HeroSection,
    TrustedUs,
    Projects,
    Credentials,
    Process,
    Footer,
  },
}
</script>

<style>
@import './styles/components.css';
@import './styles/variables.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--color-main);
  margin-top: 20px;
}
</style>
