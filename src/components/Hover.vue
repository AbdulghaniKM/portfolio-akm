<template>
    <div class="gradient-overlay"></div>
</template>

<script>
export default {
    name: 'MouseFollowGradient',
    data() {
        return {
            x: 0,
            y: 0,
        };
    },
    mounted() {
        window.addEventListener('mousemove', this.updateGradient);
    },
    beforeDestroy() {
        window.removeEventListener('mousemove', this.updateGradient);
    },
    methods: {
        updateGradient(event) {
            this.x = event.clientX;
            this.y = event.clientY;
        },
    },
    watch: {
        x() {
            this.updateBackground();
        },
        y() {
            this.updateBackground();
        },
    },
    methods: {
        updateGradient(event) {
            this.x = event.clientX;
            this.y = event.clientY;
        },
        updateBackground() {
            this.$el.style.background = `radial-gradient(circle 400px at ${this.x}px ${this.y}px, rgba(68, 174, 161,0.10), transparent 80%)`;
        },
    },
};
</script>

<style scoped>
.gradient-overlay {
    pointer-events: none;
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 50;
    transition: background 300ms;
}
</style>