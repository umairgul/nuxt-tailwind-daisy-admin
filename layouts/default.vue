<template>
    <div class="drawer lg:drawer-open">
        <input id="my-drawer-3" type="checkbox" class="drawer-toggle" />
        <div class="drawer-content flex flex-col bg-gray-50">
            <!-- Navbar -->
            <Navbar />
            <!-- Page content here -->
            <slot />
        </div>
        <!-- Drawer -->
        <Sidebar />
    </div>
</template>