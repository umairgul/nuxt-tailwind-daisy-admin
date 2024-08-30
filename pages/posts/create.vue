<template>
    <div>
        <div class="border-t">
            <div class="breadcrumbs max-w-full text-sm bg-base-200 border-b">
                <ul class="px-4">
                    <li><a>Home</a></li>
                    <li><a>Posts</a></li>
                    <li><a>Create Posts</a></li>
                </ul>
            </div>
        </div>
        <div class="lg:p-10">
            <div class="card bg-base-100 w-full lg:w-6/12">
                <div class="card-body">
                    <div class="header flex items-center justify-between">
                        <h2 class="card-title">Create Post</h2>
                        <div id="action_buttons" class="flex items-center gap-2">
                            <BackButton href="/posts" />
                        </div>
                    </div>
                    <div class="card-content mt-2 lg:mt-4">
                        <form action="#">
                            <FormControl label="Title">
                                <TextInput name="title" />
                            </FormControl>
                            <FormControl label="Description">
                                <TextArea name="description" />
                            </FormControl>
                            <FormControl label="Featured Image">
                                <FileInput name="image" />
                            </FormControl>
                            <FormControl class="items-center">
                                <SubmitButton />
                            </FormControl>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>