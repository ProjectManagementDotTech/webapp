<template>
    <div>
        <alert type="warning">
            <p class="font-cursive my-4 text-4xl text-center">Welcome to PMTech</p>
        </alert>
        <div class="flex flex-wrap items-start w-full">
            <article class="border mx-auto rounded-lg shadow-md w-11/12 md:w-5/12">
                <header class="bg-gray-100 border-b border-gray-300 px-2 py-1 text-2xl text-center text-gray-800">
                    All tools at your disposal
                </header>
                <main class="pb-1 px-2">
                    <p>All tools a project manager or a project management office needs in one place:</p>
                    <ul class="list-disc list-inside pl-4">
                        <li>Timesheet management</li>
                    </ul>
                </main>
            </article>
            <article class="border mt-4 md:mt-0 mx-auto rounded-lg shadow-md w-11/12 md:w-5/12">
                <header class="bg-gray-100 border-b border-gray-300 px-2 py-1 text-2xl text-center text-gray-800">
                    Ease of use
                </header>
                <main class="pb-1 px-2">
                    <p>See tasks due and start working on them from your dashboard!</p>
                </main>
            </article>
        </div>
        <div class="mt-8 text-center w-full">
            <router-link class="btn btn-call-to-action" to="/register">Register now</router-link>
            <router-link class="btn btn-call-to-action-2 ml-4" to="/login">Login</router-link>
        </div>
    </div>
</template>

<script>
    import Alert from "@/components/visuals/Alert";

    export default {
        components: {
            Alert
        },
        name: "Welcome"
    };

</script>

<style scoped>

</style>