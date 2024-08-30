<template>
    <div>
        <div class="border-t">
            <div class="breadcrumbs max-w-full text-sm bg-base-200 border-b">
                <ul class="px-4">
                    <li><a>Home</a></li>
                </ul>
            </div>
        </div>
        <div class="lg:p-10">
            <Card>
                <template #header>
                    <div class="card-title">Dashboard</div>
                    <Actions>
                        <AddButton />
                    </Actions>
                </template>
                <div class="card-content mt-2 lg:mt-4">
                    <div class="flex flex-col lg:flex-row items-center gap-4">
                        <div class="stats shadow gap-10">
                            <div class="stat">
                                <div class="stat-title">Total Page Views</div>
                                <div class="stat-value">89,400</div>
                                <div class="stat-desc">21% more than last month</div>
                            </div>
                        </div>

                        <div class="stats shadow gap-10">
                            <div class="stat">
                                <div class="stat-title">Total Page Views</div>
                                <div class="stat-value">89,400</div>
                                <div class="stat-desc">21% more than last month</div>
                            </div>
                        </div>
                    </div>
                </div>
            </Card>
        </div>
    </div>
</template>