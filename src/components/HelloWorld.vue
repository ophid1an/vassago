<script setup lang="ts"></script>

<template>
  <head>
    <meta name="viewport" content="width=device-width" />
  </head>
  <body>
    <main class="min-h-screen w-full bg-slate-50 text-slate-900">
      <div class="mx-auto w-full max-w-5xl px-4 py-8 sm:px-6 lg:px-8">
        <header
          class="flex w-full flex-col items-center gap-4 text-center sm:items-start sm:text-left"
        >
          <img
            class="w-full rounded-2xl object-cover shadow-sm h-44 sm:h-60 md:h-72"
            alt="background image"
            src="/src/assets/1761618748765.webp"
            referrerpolicy="same-origin"
          />
          <div class="relative flex w-full justify-center sm:justify-start">
            <img
              class="rounded-xl ml-3 -mt-28 h-30 object-cover"
              alt="avatar"
              src="/src/assets/1764646712866.webp"
              referrerpolicy="same-origin"
            />
          </div>
          <h1 class="text-2xl sm:text-4xl font-bold tracking-tight">
            Ioannis Dermentzoglou - Resume
          </h1>
        </header>

        <section
          class="mt-6 rounded-2xl border border-slate-200 bg-white p-4 sm:p-6 shadow-sm"
        >
          <h2 class="text-lg sm:text-xl font-semibold">
            Ioannis Dermentzoglou
          </h2>
          <p class="mt-1 text-sm sm:text-base text-slate-600">
            <span class="font-semibold text-slate-900">Software Engineer</span>
            <span class="mx-2 text-slate-400">|</span>
            <span>Mnesia, Erlang</span>
          </p>
        </section>

        <section
          class="mt-6 rounded-2xl border border-slate-200 bg-white p-4 sm:p-6 shadow-sm"
        >
          <h2 class="text-xl sm:text-2xl font-semibold">Technical Skills</h2>
          <div class="mt-4 space-y-4">
            <div>
              <h3
                class="text-xs font-semibold uppercase tracking-wide text-slate-500"
              >
                Languages &amp; Frameworks
              </h3>
              <div class="mt-2 flex flex-wrap gap-2">
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Erlang</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >TypeScript</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >PHP - Laravel</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >PHP - Symfony</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Scala</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >C</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Python</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Java</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >React</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >React Native</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Vue</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Vuetify</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >ShadCN</span
                >
              </div>
            </div>
            <div>
              <h3
                class="text-xs font-semibold uppercase tracking-wide text-slate-500"
              >
                Databases
              </h3>
              <div class="mt-2 flex flex-wrap gap-2">
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Mnesia</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >PostgreSQL</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >MongoDB</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >MariaDB</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Cassandra</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Neo4j</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Prometheus</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >HBase</span
                >
              </div>
            </div>
            <div>
              <h3
                class="text-xs font-semibold uppercase tracking-wide text-slate-500"
              >
                Cloud &amp; Infrastructure
              </h3>
              <div class="mt-2 flex flex-wrap gap-2">
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >AWS / EC2 - ECS - ECR</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >DigitalOcean / DO Spaces</span
                >
              </div>
            </div>
            <div>
              <h3
                class="text-xs font-semibold uppercase tracking-wide text-slate-500"
              >
                DevOps &amp; Tools
              </h3>
              <div class="mt-2 flex flex-wrap gap-2">
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Apache Spark</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Apache Flink</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >PyTorch</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >TensorFlow / Keras</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Docker Offerings</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >CI/CD</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Nginx</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Server Admin</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Systems Management</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Git - GitHub / GitLab / Bitbucket</span
                >
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Jira</span
                >
              </div>
            </div>
            <div>
              <h3
                class="text-xs font-semibold uppercase tracking-wide text-slate-500"
              >
                Core Competencies
              </h3>
              <div class="mt-2 flex flex-wrap gap-2">
                <span
                  class="rounded-full bg-slate-100 px-3 py-1 text-sm text-slate-700"
                  >Software Design</span
                >
              </div>
            </div>
          </div>
        </section>

        <section
          class="mt-6 rounded-2xl border border-slate-200 bg-white p-4 sm:p-6 shadow-sm"
        >
          <h2 class="text-xl sm:text-2xl font-semibold">Education</h2>
          <div class="mt-4 space-y-4">
            <div class="rounded-xl border border-slate-100 bg-slate-50 p-4">
              <h3 class="text-base font-semibold">
                Aristotle University of Thessaloniki (AUTH)
              </h3>
              <p class="mt-1 text-sm text-slate-600">Oct 2017 - Oct 2019</p>
              <p class="mt-2 text-sm font-semibold text-slate-900">
                Master's degree, Knowledge, Data, and Software Technologies
              </p>
              <p class="mt-2 text-sm text-slate-700">
                <span class="font-semibold text-slate-900">Coursework:</span>
                Machine learning, big data, spatial and multimedia DBs,
                automated planning and scheduling, PC hardware architecture
              </p>
              <p class="mt-2 text-sm text-slate-700">
                <span class="font-semibold text-slate-900">Technologies:</span>
                Python Pandas, PyTorch, Apache Spark, Scala, HBase, PostgreSQL,
                Cassandra, Neo4j, PDDL, C
              </p>
            </div>
            <div class="rounded-xl border border-slate-100 bg-slate-50 p-4">
              <h3 class="text-base font-semibold">Hellenic Open University</h3>
              <p class="mt-1 text-sm text-slate-600">2012 - 2017</p>
              <p class="mt-2 text-sm font-semibold text-slate-900">
                Bachelor's degree, Computer Science
              </p>
            </div>
          </div>
        </section>

        <section
          class="mt-6 rounded-2xl border border-slate-200 bg-white p-4 sm:p-6 shadow-sm"
        >
          <h2 class="text-xl sm:text-2xl font-semibold">Contact</h2>
          <div class="mt-4 grid gap-3 sm:grid-cols-2">
            <div class="rounded-lg border border-slate-100 bg-slate-50 p-4">
              <p
                class="text-xs font-semibold uppercase tracking-wide text-slate-500"
              >
                Email
              </p>
              <a
                href="mailto:dermentzoglou.ioannis@gmail.com"
                class="mt-1 block text-sm font-medium text-slate-700 underline decoration-slate-300 underline-offset-4 hover:text-slate-900"
                rel="noopener noreferrer"
                data-token-index="2"
                tabindex="0"
                >dermentzoglou.ioannis@gmail.com</a
              >
            </div>
            <div class="rounded-lg border border-slate-100 bg-slate-50 p-4">
              <p
                class="text-xs font-semibold uppercase tracking-wide text-slate-500"
              >
                LinkedIn
              </p>
              <a
                href="https://www.linkedin.com/in/giannis-dermentzoglou-0a6381164/overlay/about-this-profile/?trk=opento_sprofile_details"
                class="mt-1 inline-flex items-center text-sm font-medium text-slate-700 underline decoration-slate-300 underline-offset-4 hover:text-slate-900"
                rel="noopener noreferrer"
                data-token-index="2"
                tabindex="0"
                >Profile</a
              >
            </div>
          </div>
        </section>
      </div>
    </main>
  </body>
</template>

<style scoped></style>
