<script>
    // You can import your logo image here
    // import logo from './path_to_your_logo.png';
</script>

<style>
    /* You can use Tailwind CSS classes directly in your Svelte component */
    /* Here, we're using flexbox to layout the sidebar */
    .sidebar {
        @apply h-screen bg-gray-800 text-white flex flex-col;
        width: 240px; /* Set the width of the sidebar */
    }

    .project-name {
        @apply p-4 text-lg font-semibold;
    }

    /* .logo {
        @apply p-4;
    } */

    .fields {
        @apply flex-grow;
    }

    .field {
        @apply p-4 cursor-pointer hover:bg-gray-700;
    }
</style>

<div class="sidebar">
    <div class="project-name">SMART PEAGE</div>
    <!-- <div class="logo">
        <img src={logo} alt="Logo" class="h-8 w-auto" />
        <span class="text-lg font-semibold">SMART PEAGE</span>
    </div> -->
    <div class="fields">
        <div class="field">Stats</div>
        <div class="field">Tarifs</div>
        <div class="field">Vehicules</div>
    </div>
</div>


