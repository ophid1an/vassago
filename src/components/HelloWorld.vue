<script setup lang="ts"></script>

<template>
  <div class="flex flex-col items-center">
    <img
      class="block object-cover rounded rounded-lg h-10 object-center"
      alt="background image"
      src="/src/assets/1761618748765.webp"
      referrerpolicy="same-origin"
    />
    <div
      role="button"
      tabindex="0"
      class="select-none [transition:background_20ms_ease-in] cursor-pointer flex items-center justify-center h-[140px] w-[140px] rounded-[0.25em] shrink-0 relative z-[1] ms-[3px] mb-0 -mt-20 pointer-events-auto"
      aria-label="Change page icon"
    >
      <img
        class="block object-cover rounded-lg rounded"
        alt="avatar"
        src="/src/assets/1764646712866.webp"
        referrerpolicy="same-origin"
      />
    </div>
    <div
      class="text-[var(--c-texPri)] font-bold leading-[1.2] text-[40px] font-[ui-sans-serif,_-apple-system,_BlinkMacSystemFont,_'Segoe_UI_Variable_Display',_'Segoe_UI',_Helvetica,_'Apple_Color_Emoji',_Arial,_sans-serif,_'Segoe_UI_Emoji',_'Segoe_UI_Symbol'] cursor-text flex items-center"
    >
      <h1
        class="pt-[3px] pb-0 px-0.5 text-[1em] font-[inherit] m-0 cursor-text"
        placeholder="New page"
      >
        <span data-token-index="0" class="inline"
          >Ioannis Dermentzoglou - Resume</span
        >
      </h1>
    </div>
  </div>

  <div
    class="shrink-0 grow max-w-full flex items-start flex-col text-base leading-[1.5] w-full z-[4] pt-2 pb-0 px-0"
  >
    <h2 placeholder="Heading 1">Ioannis Dermentzoglou</h2>

    <span data-token-index="0" class="font-semibold">Software Engineer</span>
    | Mnesia, Erlang

    <div
      class="flex items-center justify-center pointer-events-auto w-full h-[13px] flex-none"
    >
      <div
        class="w-full h-px visible [border-bottom:1px_solid_var(--ca-borPriTra)]"
        role="separator"
      ></div>

      <h3 class="p-2" placeholder="Heading 2">Technical Skills</h3>

      <h4 class="p-2" placeholder="Heading 3">Languages &amp; Frameworks</h4>

      <span class="p-2"> Erlang </span>

      <span class="p-2"> React.js </span>

      <span class="p-2"> React Native </span>

      <span class="p-2"> Vue.js </span>

      <span class="p-2"> Vuetify </span>

      <span class="p-2"> Laravel </span>

      <span class="p-2"> Symfony Framework </span>

      <h4 class="p-2" placeholder="Heading 3">Databases</h4>

      <span class="p-2"> Mnesia </span>

      <span class="p-2"> PostgreSQL ></span>

      <span class="p-2"> MongoDB </span>

      <span class="p-2"> MariaDB </span>

      <h4 class="p-2" placeholder="Heading 3">Cloud &amp; Infrastructure</h4>

      <span class="p-2"> Amazon Web Services (AWS) </span>

      <span class="p-2"> Amazon EC2 </span>

      <span class="p-2"> Amazon ECS </span>

      <span class="p-2"> Amazon Elastic Container Registry (ECR) </span>

      <span class="p-2"> DigitalOcean </span>

      <span class="p-2"> DO Spaces </span>

      <h4 class="p-2" placeholder="Heading 3">DevOps &amp; Tools</h4>

      <span class="p-2"> Docker Offerings </span>

      <span class="p-2"> CI/CD </span>

      <span class="p-2"> Nginx </span>

      <span class="p-2"> Server Admin </span>

      <span class="p-2"> Systems Management </span>

      <span class="p-2"> Jira </span>

      <span class="p-2"> GitHub </span>

      <h4 class="p-2" placeholder="Heading 3">Core Competencies</h4>

      <span class="p-2"> Software Design </span>

      <div
        class="flex items-center justify-center pointer-events-auto w-full h-[13px] flex-none"
      >
        <div
          class="w-full h-px visible [border-bottom:1px_solid_var(--ca-borPriTra)]"
          role="separator"
        ></div>

        <h3 class="p-2" placeholder="Heading 2">Education</h3>

        <h4 class="p-2" placeholder="Heading 3">
          Aristotle University of Thessaloniki (AUTH)
        </h4>

        <span data-token-index="0" class="font-semibold"
          >Master's degree, Knowledge, Data, and Software Technologies</span
        >

        <span data-token-index="0" class="italic">Oct 2017 - Oct 2019</span>

        <span data-token-index="0" class="font-semibold">Coursework</span>:
        Machine learning, big data, spatial and multimedia DBs, automated
        planning and scheduling, PC hardware architecture

        <span data-token-index="0" class="font-semibold">Technologies</span>:
        Python Pandas, PyTorch, Apache Spark, Scala, HBase, PostgreSQL,
        Cassandra, Neo4j, PDDL, C

        <h4 class="p-2" placeholder="Heading 3">Hellenic Open University</h4>

        <span data-token-index="0" class="font-semibold"
          >Bachelor's degree, Computer Science</span
        >

        <span data-token-index="0" class="italic">2012 - 2017</span>
      </div>
      <div
        class="flex items-center justify-center pointer-events-auto w-full h-[13px] flex-none"
      >
        <div
          class="w-full h-px visible [border-bottom:1px_solid_var(--ca-borPriTra)]"
          role="separator"
        ></div>

        <h3 class="p-2" placeholder="Heading 2">Contact</h3>

        <div class="flex gap-2 w-full p-3">
          <span class="font-semibold">Email: </span>
          <a
            href="mailto:dermentzoglou.ioannis@gmail.com"
            class="cursor-pointer text-[inherit] [word-wrap:break-word] decoration-[inherit]"
            rel="noopener noreferrer"
            data-token-index="2"
            tabindex="0"
            ><span
              class="underline decoration-[0.05em] decoration-[var(--ca-opaLinDecCol)] underline-offset-[10%] opacity-70"
              >dermentzoglou.ioannis@gmail.com</span
            ></a
          >

          <div class="flex gap-2 w-full p-3">
            <span class="font-semibold">LinkedIn: </span>
            <a
              href="https://www.linkedin.com/in/giannis-dermentzoglou-0a6381164/overlay/about-this-profile/?trk=opento_sprofile_details"
              class="cursor-pointer"
              rel="noopener noreferrer"
              data-token-index="2"
              tabindex="0"
              ><span class="underline opacity-70">Profile</span></a
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
