<template>
  <section class="projects">
    <h3>Lemon42 proudly presents:</h3>
    <ProjectCard>
      <template v-slot:header>
        <h3>Project 1</h3>
      </template>
      <template v-slot:image>
        <img src="" alt="awesome something" />
      </template>
      <template v-slot:body>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil ut esse
          illum odio sed exercitationem et commodi quibusdam eum adipisci!
        </p>
      </template>
      <template v-slot:footer>
        <a href="#">Description</a>
        <a href="#">Live</a>
      </template>
    </ProjectCard>
    <ProjectCard>
      <template v-slot:header>
        <h3>Project 2</h3>
      </template>
      <template v-slot:image>
        <img src="" alt="awesome something" />
      </template>
      <template v-slot:body>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil ut esse
          illum odio sed exercitationem et commodi quibusdam eum adipisci!
        </p>
      </template>
      <template v-slot:footer>
        <a href="#">Description</a>
        <a href="#">Live</a>
      </template>
    </ProjectCard>
    <ProjectCard>
      <template v-slot:header>
        <h3>Project 3</h3>
      </template>
      <template v-slot:image>
        <img src="" alt="awesome something" />
      </template>
      <template v-slot:body>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil ut esse
          illum odio sed exercitationem et commodi quibusdam eum adipisci!
        </p>
      </template>
      <template v-slot:footer>
        <a href="#">Description</a>
        <a href="#">Live</a>
      </template>
    </ProjectCard>
    <ProjectCard>
      <template v-slot:header>
        <h3>Project 4</h3>
      </template>
      <template v-slot:image>
        <img src="" alt="awesome something" />
      </template>
      <template v-slot:body>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil ut esse
          illum odio sed exercitationem et commodi quibusdam eum adipisci!
        </p>
      </template>
      <template v-slot:footer>
        <a href="#">Description</a>
        <a href="#">Live</a>
      </template>
    </ProjectCard>
    <ProjectCard>
      <template v-slot:header>
        <h3>Project 5</h3>
      </template>
      <template v-slot:image>
        <img src="" alt="awesome something" />
      </template>
      <template v-slot:body>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil ut esse
          illum odio sed exercitationem et commodi quibusdam eum adipisci!
        </p>
      </template>
      <template v-slot:footer>
        <a href="#">Description</a>
        <a href="#">Live</a>
      </template>
    </ProjectCard>
    <ProjectCard>
      <template v-slot:header>
        <h3>Project 6</h3>
      </template>
      <template v-slot:image>
        <img src="" alt="awesome something" />
      </template>
      <template v-slot:body>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil ut esse
          illum odio sed exercitationem et commodi quibusdam eum adipisci!
        </p>
      </template>
      <template v-slot:footer>
        <a href="#">Description</a>
        <a href="#">Live</a>
      </template>
    </ProjectCard>
    <div>
      <h4>Check out our other aweasome projects</h4>
      <h2>Right Here</h2>
    </div>
  </section>
</template>

<script>
import ProjectCard from './ProjectCard'

export default {
  components: {
    ProjectCard,
  },
}
</script>

<style></style>
