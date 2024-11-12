<template>
    <div
            v-if="user"
            class="fixed inset-0 bg-black bg-opacity-50 flex justify-center items-center z-50"
    >
        <div class="relative p-4 w-full max-w-2xl max-h-full">
            <!-- Modal content -->
            <div class="relative bg-white rounded-lg shadow dark:bg-gray-700">
                <!-- Modal header -->
                <div class="flex items-center justify-between p-4 md:p-5">
                    <h3 class="text-3xl font-semibold text-gray-500 text-gray-900 dark:text-white">
                        {{ user.name.first }} {{ user.name.last }}
                    </h3>
                    <button
                            type="button"
                            class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm w-8 h-8 ms-auto inline-flex justify-center items-center dark:hover:bg-gray-600 dark:hover:text-white"
                            data-modal-hide="default-modal"
                            @click="close"
                    >
                        <svg
                                class="w-3 h-3"
                                aria-hidden="true"
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 14 14"
                        >
                            <path
                                    stroke="currentColor"
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"
                            />
                        </svg>
                        <span class="sr-only">Close modal</span>
                    </button>
                </div>
                <!-- Modal body -->
                <div class="p-4 md:p-5 space-y-4 pb-2.5">

                    <table class="w-full text-sm text-left text-gray-700 dark:text-gray-300">
                        <tbody>
                        <tr>
                            <td class="py-2 text-gray-500">Date:</td>
                            <td class="py-2">{{ formatDate(user.registered.date) }}</td>
                        </tr>
                        <tr>
                            <td class="py-2 text-gray-500">Gender:</td>
                            <td class="py-2">{{ formatGender(user.gender) }}</td>
                        </tr>
                        <tr>
                            <td class="py-2 text-gray-500">Country:</td>
                            <td class="py-2">{{ user.location.country }}</td>
                        </tr>
                        <tr>
                            <td class="py-2 text-gray-500">Email:</td>
                            <td class="py-2">{{ user.email }}</td>
                        </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>

    <!-- Main modal -->
</template>

<script>
    export default {
        props: {
            user: Object,
        },
        methods: {
            close() {
                this.$emit('close');
            },
            formatGender(gender) {
                return gender.charAt(0).toUpperCase() + gender.slice(1); // Capitalizes the first letter
            },
            formatDate(dateString) {
                const date = new Date(dateString);
                const options = { year: 'numeric', month: 'long', day: 'numeric' };
                return date.toLocaleDateString('en-GB', options); // Formats date as "14 July, 2021"
            },
        },
    };
</script>

<style scoped>
    /* Tailwind classes for modal */
    .bg-black {
        background-color: rgba(0, 0, 0, 0.5);
    }
</style>