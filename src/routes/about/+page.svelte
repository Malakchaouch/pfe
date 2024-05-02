<style>
    /* You can use Tailwind CSS classes directly in your Svelte component */
    /* Center the content horizontally and vertically */
    .container {
        @apply flex justify-center items-center h-full;
    }

    /* Style for the sidebar */
    .sidebar {
        @apply h-screen bg-gray-800 text-white flex flex-col;
        width: 240px; /* Set the width of the sidebar */
    }

    .square {
        @apply bg-gray-200 p-4 flex justify-center items-center;
        height: 200px;
    }

    .chart {
        @apply p-4;
    }
</style>

<div class="sidebar">
    <div class="container">
        <div class="grid grid-cols-2 gap-4">
            <div class="col-span-2 md:col-span-1">
                <div class="grid grid-cols-2 gap-4">
                    <div class="square">
                        <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Button 1</button>
                    </div>
                    <div class="square">
                        <button class="bg-green-500 hover:bg-green-700 text-white font-bold py-2 px-4 rounded">Button 2</button>
                    </div>
                    <div class="square">
                        <button class="bg-yellow-500 hover:bg-yellow-700 text-white font-bold py-2 px-4 rounded">Button 3</button>
                    </div>
                    <div class="square">
                        <button class="bg-red-500 hover:bg-red-700 text-white font-bold py-2 px-4 rounded">Button 4</button>
                    </div>
                </div>
            </div>
            <div class="col-span-2 md:col-span-1">
                <div class="chart">
                    <!-- Bar chart goes here -->
                    <div>Bar Chart</div>
                </div>
            </div>
            <div class="col-span-2 md:col-span-1">
                <div class="chart">
                    <!-- Line chart goes here -->
                    <div>Line Chart</div>
                </div>
            </div>
            <div class="col-span-2 md:col-span-1">
                <div class="chart">
                    <!-- Donut chart goes here -->
                    <div>Donut Chart</div>
                </div>
            </div>
        </div>
    </div>
</div>
