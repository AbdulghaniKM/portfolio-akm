<template>
    <div class="bg-mainBg text-white min-h-screen font-InterVar">
        <header class="z-30 fixed w-full top-0 sm:hidden">
            <div class="bg-mainBg text-center z-50">
                <ul class="flex flex-col xs:flex-row justify-center items-center space-x-8 py-2 text-header">
                    <li class="cursor-pointer z-50 focus:text-glow my-2 xs:my-0">
                        <a href="#about" class="btn btn-ghost cursor-pointer z-50 hover:text-glow">About</a>
                    </li>
                    <li class="my-2 xs:my-0">
                        <a href="#projects" class="btn btn-ghost cursor-pointer z-50  hover:text-glow">Projects</a>
                    </li>
                </ul>
            </div>
        </header>
        <main class="bg-mainBg sm:-mt-[5rem]">
            <section id="about"
                class=" min-h-screen  flex flex-col items-center justify-center pt-12 px-8   transition-opacity mt-[4rem] sm:top-0">
                <div class="grid grid-cols-1 xs:grid-cols-2 gap-10">
                    <div class="text-center xs:text-left">
                        <h1 class="text-4xl xs:text-5xl font-bold">Abdulghani Khalid</h1>
                        <h2 class="mt-2 text-xl xs:text-2xl text-lightBlue">Junior Frontend Developer</h2>
                        <p class="text-base xs:text-lg mt-4 text-mainTxt">I build pixel-perfect, engaging,<br> and
                            accessible digital experiences.</p>
                        <ul class="flex flex-row justify-center xs:justify-start">
                            <li class="mt-4" title="LinkedIn">
                                <a href="https://www.linkedin.com/in/abdulghani-khalid-mohsin-647278243/"
                                    target="_blank">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
                                        <path
                                            d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"
                                            fill="#8890b1" />
                                    </svg>
                                </a>
                            </li>
                            <li class="mt-4 ml-4" title="GitHub">
                                <a href="https://github.com/AbdulghaniKM" target="_blank">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
                                        <path
                                            d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
                                            fill="#8890b1" />
                                    </svg>
                                </a>
                            </li>
                            <li class="mt-4 ml-4" title="Instagram">
                                <a href="https://instagram.com/abdulghani_k.m" target="_blank">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
                                        <path
                                            d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"
                                            fill="#8890b1" />
                                    </svg>
                                </a>
                            </li>
                        </ul>
                    </div>
                    <div class="text-center xs:text-left sm:text-left">
                        <h1
                            class="hidden sm:block text-mainTxt text-3xl font-InterVar font-bold sm:text-center sm:mb-7">
                            About
                        </h1>
                        <p class="text-mainTxt">
                            Commencing in 2023, I embarked on a journey of <span class="text-glow"> self-learning
                            </span> within the realm of web
                            development. During this time as a student, I garnered a wealth of knowledge while actively
                            engaging in various projects. By early 2024, I witnessed significant <span
                                class="text-glow">growth</span> in my skills,
                            transitioning to collaborative work within a team environment on tangible projects for
                            clients.
                        </p>
                        <br>
                        <p class="text-mainTxt">
                            My expertise lies in a structured understanding of <span class="text-glow">HTML</span>,
                            <span class="text-glow">CSS</span>, and <span class="text-glow">JS</span>. Additionally, I
                            employ web frameworks to augment both the functionality and productivity of my projects.
                            Among these frameworks are <span class="text-glow">Vue.js</span> and <span
                                class="text-glow">Tailwind CSS</span>. I also utilize UI components like <span
                                class="text-glow">DaisyUI</span>.
                        </p>
                    </div>
                </div>
            </section>
            <section id="projects"
                class="min-h-screen flex flex-col items-center justify-center px-8 transition-opacity mt-20 sm:mt-5">
                <div class="mb-2">
                    <h1 class="text-mainTxt text-3xl font-InterVar font-bold">
                        Projects
                    </h1>
                </div>
                <div class="grid grid-cols-1 xs:grid-cols-2 gap-10">
                    <div class="card glass w-full xs:w-96 bg-transparent shadow-2xl" v-for="project in projects"
                        :key="project.id">
                        <figure class="px-10 pt-10">
                            <img :src="project.image" class="rounded-xl" />
                        </figure>
                        <div class="card-body items-center text-center">
                            <h2 class="card-title">
                                {{ project.name }}
                            </h2>
                            <p>
                                {{ project.description }}
                            </p>
                            <div class="flex justify-center items-center gap-4">
                                <div v-if="project.tech && project.tech.length" class="badge bg-mainBg text-glow"
                                    v-for="(tech, index) in project.tech" :key="index">
                                    {{ tech }}
                                </div>
                            </div>
                            <div class="card-actions">
                                <button class="btn bg-mainTxt text-mainBg hover:bg-mainBg hover:text-glow outline-none">
                                    <a :href="project.link" target="_blank">
                                        Visit!
                                    </a>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>
    </div>
</template>
<script>
export default {
    data() {
        return {
            projects: [
                { id: 1, name: "Units Converter", description: "A unit converter application that allows users to convert between units of length.", image: './src/assets/img/converter.jpg', link: 'https://unit-converter-akmcode.netlify.app/', tech: ['Vue.js', 'Tailwind CSS', 'DaisyUI'] },
                { id: 2, name: "To-Do List", description: "A to-do list application that allows users to create, edit, and delete to-do items.", image: './src/assets/img/todo.jpg', link: 'https://to-do-lsit-akmcode.netlify.app/', tech: ['Vue.js', 'Tailwind CSS', 'DaisyUI'] },
                { id: 3, name: "Tic Tac Toe", description: "A tic-tac-toe game.", image: './src/assets/img/TicTacToe.png', link: 'https://basic-tic-tac-toe-akmcode.netlify.app/', tech: ['Vue.js', 'Tailwind CSS'] },
                { id: 4, name: "Weather App", description: "A weather application that allows users to search for a city and view the current weather.", image: './src/assets/img/Weather.png', link: 'https://weatherapp-akmcode.netlify.app/', tech: ['HTML', 'CSS', 'JavaScript'] },
                { id: 5, name: "Tic Tac Toe", description: "A tic-tac-toe game.", image: './src/assets/img/TicTacToe2.png', link: 'https://basic-tic-tac-toe-akmcode.netlify.app/', tech: ['HTML', 'CSS', 'JavaScript'] },
            ]

        };
    },
    mounted() {
        const sections = document.querySelectorAll('section');

        const options = {
            root: null,
            threshold: 0.1,
            rootMargin: '0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('in-view');
                } else {
                    entry.target.classList.remove('in-view');
                }
            });
        }, options);

        sections.forEach(section => {
            observer.observe(section);
        });
    }
};
</script>

<style>
:root {
    --darkBlue: #0a182e;
    --lightBlue: #64ffda;
}

body {
    background-color: var(--darkBlue);
    color: white;
    scroll-behavior: smooth;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header ul {
    flex-wrap: wrap;
}

section.in-view {
    opacity: 1;
    transform: translateY(0);
}

section {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 1s ease-out, transform 1s ease-out;
}

.card img {
    width: 100%;
    height: auto;
}
</style>
