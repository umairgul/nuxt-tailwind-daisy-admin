<template>
    <div>
        <div class="border-t">
            <div class="breadcrumbs max-w-full text-sm bg-base-200 border-b">
                <ul class="px-4">
                    <li><a href="#">Home</a></li>
                    <li><a>Posts</a></li>
                </ul>
            </div>
        </div>
        <div class="lg:p-10">
            <div class="card bg-base-100 w-full">
                <div class="card-body">
                    <div class="header flex items-center justify-between">
                        <h2 class="card-title">Posts</h2>
                        <div id="action_buttons" class="flex items-center gap-2">
                            <AddButton href="/posts/create" />
                        </div>
                    </div>
                    <div class="card-content mt-2 lg:mt-4">
                        <div class="overflow-x-auto">
                            <table class="table table-zebra border">
                                <thead>
                                    <tr>
                                        <th width="5%">ID</th>
                                        <th width="60%">Title</th>
                                        <th width="10%">Author</th>
                                        <th width="10%">Created At</th>
                                        <th width="10%" class="text-end">Action</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <td>1</td>
                                        <td>Impact of CSS</td>
                                        <td>John Doe</td>
                                        <td>29 August 2024</td>
                                        <td>
                                            <Actions>
                                                <EditButton />
                                                <DeleteButton />
                                            </Actions>
                                        </td>
                                    </tr>
                                    <tr>
                                        <td>1</td>
                                        <td>Impact of CSS</td>
                                        <td>John Doe</td>
                                        <td>29 August 2024</td>
                                        <td>
                                            <Actions>
                                                <EditButton />
                                                <DeleteButton />
                                            </Actions>
                                        </td>
                                    </tr>
                                    <tr>
                                        <td>1</td>
                                        <td>Impact of CSS</td>
                                        <td>John Doe</td>
                                        <td>29 August 2024</td>
                                        <td>
                                            <Actions>
                                                <EditButton />
                                                <DeleteButton />
                                            </Actions>
                                        </td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>