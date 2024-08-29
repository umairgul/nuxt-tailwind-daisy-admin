<template>
    <div class="navbar bg-base-200 w-full">
        <div class="flex-none lg:hidden">
            <label for="my-drawer-3" aria-label="open sidebar" class="btn btn-square btn-ghost">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                    class="inline-block h-6 w-6 stroke-current">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16">
                    </path>
                </svg>
            </label>
        </div>
        <div class="mx-2 flex-1 px-2">
            <span class="text-lg font-semibold">Laravel</span>
        </div>
        <div class="hidden flex-none lg:block">
            <div class="dropdown dropdown-end">
                <div tabindex="0" role="button" class="btn btn-ghost">Admin</div>
                <ul tabindex="0" class="dropdown-content menu bg-base-100 rounded-box z-[1] w-52 p-2 shadow">
                    <li><a>Profile</a></li>
                    <li><a>Logout</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>