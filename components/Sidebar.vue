<template>
    <div class="drawer-side border">
        <label for="my-drawer-3" aria-label="close sidebar" class="drawer-overlay"></label>
        <ul class="menu bg-base-200 min-h-full w-56 p-4">
            <!-- Sidebar content here -->
            <li>
                <NuxtLink to="/">
                    <img src="/assets/images/logo.png" />
                </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/posts">Posts</NuxtLink>
            </li>
            <li><a>Categories</a></li>
            <li><a>Tags</a></li>
            <li>
                <details>
                    <summary>Account</summary>
                    <ul>
                        <li><a>Profile</a></li>
                        <li><a>Log out</a></li>
                    </ul>
                </details>
            </li>
        </ul>
    </div>
</template>