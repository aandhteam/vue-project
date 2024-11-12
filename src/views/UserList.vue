<template>
    <div class="w-full mx-auto bg-white rounded-lg shadow-md gap-6">

        <div class="container">
            <div class="w-11/12 mx-auto mt-3 mb-3 flex justify-between">
                <div class="w-[500px]">
                    <img src="/assets/img/logo-1.png" alt="User Avatar" class="w-44 object-cover"/>
                </div>
                <div class="icon-container flex gap-3 mt-4">
                <span class="block w-[24px]">
                    <svg width="17" height="20" viewBox="0 0 17 20" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M16.649 15.9161C16.5859 15.878 16.1106 15.568 15.6346 14.6303C14.7606 12.9084 14.5772 10.4827 14.5772 8.75098C14.5772 8.74344 14.577 8.73598 14.5767 8.72848C14.5672 6.43984 13.095 4.46695 10.9884 3.58176V2.22797C10.9884 0.999453 9.91652 0 8.599 0H8.40099C7.08347 0 6.0116 0.999453 6.0116 2.22797V3.58168C3.8979 4.46973 2.42282 6.45269 2.42282 8.75098C2.42282 10.4827 2.23937 12.9083 1.36535 14.6303C0.889457 15.568 0.414156 15.8779 0.350962 15.9161C0.0848405 16.0308 -0.0463739 16.2956 0.0148482 16.564C0.0766579 16.8351 0.348822 17.022 0.646037 17.022H5.2596C5.28537 18.6681 6.7286 20 8.50002 20C10.2714 20 11.7147 18.6681 11.7404 17.022H16.354C16.6512 17.022 16.9234 16.8351 16.9852 16.564C17.0463 16.2956 16.9151 16.0307 16.649 15.9161ZM7.2705 2.22797C7.2705 1.64668 7.77764 1.17379 8.40103 1.17379H8.59904C9.22243 1.17379 9.72958 1.64668 9.72958 2.22797V3.20129C9.33228 3.12484 8.92102 3.08461 8.49985 3.08461C8.0788 3.08461 7.66766 3.1248 7.27054 3.20117V2.22797H7.2705ZM8.50002 18.8262C7.42273 18.8262 6.54401 18.0209 6.51846 17.022H10.4815C10.456 18.0208 9.5773 18.8262 8.50002 18.8262ZM11.0345 15.8481C11.0344 15.8481 2.0805 15.8481 2.0805 15.8481C2.18939 15.6902 2.30021 15.5113 2.41036 15.3091C3.25396 13.7606 3.68172 11.5541 3.68172 8.75098C3.68172 6.27375 5.84312 4.2584 8.49981 4.2584C11.1565 4.2584 13.3179 6.27375 13.3179 8.75293C13.3179 8.76016 13.318 8.76734 13.3183 8.77453C13.3207 11.5664 13.7484 13.765 14.5897 15.3091C14.6998 15.5113 14.8107 15.6902 14.9195 15.8481H11.0345Z"
      fill="black"/>
</svg>
                </span>
                    <span class="block w-[24px]">
                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M10.0001 5.21918C7.36401 5.21918 5.21924 7.36395 5.21924 10.0001C5.21924 12.6362 7.36401 14.7809 10.0001 14.7809C12.6362 14.7809 14.781 12.6362 14.781 10.0001C14.781 7.36395 12.6362 5.21918 10.0001 5.21918ZM10.0001 13.5857C8.02304 13.5857 6.41446 11.9771 6.41446 10.0001C6.41446 8.02298 8.02304 6.4144 10.0001 6.4144C11.9772 6.4144 13.5858 8.02298 13.5858 10.0001C13.5858 11.9771 11.9772 13.5857 10.0001 13.5857Z"
                              fill="black"/>
                        <path d="M19.5294 7.72278L17.9922 7.38861C17.8586 6.97937 17.693 6.5802 17.4976 6.19568L18.3485 4.87198C18.5005 4.63547 18.4671 4.32495 18.2684 4.12628L15.8737 1.73157C15.675 1.5329 15.3645 1.49948 15.128 1.65146L13.8043 2.50244C13.4198 2.30698 13.0206 2.14142 12.6114 2.00775L12.2772 0.470581C12.2176 0.195923 11.9743 0 11.6933 0H8.30673C8.02567 0 7.78244 0.195923 7.72278 0.470581L7.38861 2.00775C6.97937 2.14142 6.5802 2.30698 6.19568 2.50244L4.87198 1.65146C4.63547 1.49948 4.32495 1.5329 4.12628 1.73157L1.73157 4.12628C1.5329 4.32495 1.49948 4.63547 1.65146 4.87198L2.50244 6.19568C2.30698 6.5802 2.14142 6.97937 2.00775 7.38861L0.470581 7.72278C0.195923 7.78259 0 8.02567 0 8.30673V11.6933C0 11.9743 0.195923 12.2174 0.470581 12.2772L2.00775 12.6114C2.14142 13.0206 2.30698 13.4198 2.50244 13.8043L1.65146 15.128C1.49948 15.3645 1.5329 15.675 1.73157 15.8737L4.12628 18.2684C4.32495 18.4671 4.63547 18.5005 4.87198 18.3485L6.19568 17.4976C6.5802 17.693 6.97937 17.8586 7.38861 17.9922L7.72278 19.5294C7.78244 19.8041 8.02567 20 8.30673 20H11.6933C11.9743 20 12.2176 19.8041 12.2772 19.5294L12.6114 17.9922C13.0206 17.8586 13.4198 17.693 13.8043 17.4976L15.128 18.3485C15.3645 18.5005 15.675 18.4673 15.8737 18.2684L18.2684 15.8737C18.4671 15.675 18.5005 15.3645 18.3485 15.128L17.4976 13.8043C17.693 13.4198 17.8586 13.0206 17.9922 12.6114L19.5294 12.2772C19.8041 12.2174 20 11.9743 20 11.6933V8.30673C20 8.02567 19.8041 7.78259 19.5294 7.72278ZM18.8048 11.2115L17.3953 11.5179C17.1788 11.5651 17.0061 11.7281 16.9466 11.9414C16.7917 12.4969 16.5689 13.0342 16.2845 13.5382C16.1755 13.7312 16.1823 13.9687 16.3022 14.1551L17.0827 15.3691L15.3693 17.0827L14.1551 16.3022C13.9687 16.1823 13.7312 16.1755 13.5384 16.2845C13.0342 16.5689 12.4969 16.7917 11.9414 16.9466C11.7281 17.0061 11.5651 17.1788 11.5179 17.3953L11.2115 18.8048H8.78845L8.48206 17.3953C8.43491 17.1788 8.27194 17.0061 8.05862 16.9466C7.50305 16.7917 6.96579 16.5689 6.46179 16.2845C6.26877 16.1755 6.03134 16.1824 5.84488 16.3022L4.63089 17.0827L2.91748 15.3691L3.69781 14.1551C3.81775 13.9687 3.82462 13.7312 3.71567 13.5382C3.43124 13.0342 3.20847 12.4969 3.05344 11.9414C2.99393 11.7281 2.82135 11.5651 2.60483 11.5179L1.19522 11.2115V8.78845L2.60468 8.48206C2.8212 8.43491 2.99393 8.27194 3.05344 8.05862C3.20831 7.50305 3.43109 6.96579 3.71552 6.46179C3.82446 6.26877 3.81775 6.03134 3.69781 5.84488L2.91733 4.63089L4.63074 2.91733L5.84488 3.69781C6.03134 3.81775 6.26877 3.82446 6.46164 3.71552C6.96579 3.43109 7.50305 3.20831 8.05862 3.05344C8.27194 2.99393 8.43491 2.8212 8.48206 2.60468L8.78845 1.19522H11.2115L11.5179 2.60468C11.5651 2.8212 11.7281 2.99393 11.9414 3.05344C12.4969 3.20831 13.0342 3.43109 13.5382 3.71552C13.7312 3.82446 13.9687 3.8176 14.1551 3.69781L15.3691 2.91733L17.0825 4.63089L16.3022 5.84488C16.1823 6.03134 16.1754 6.26877 16.2843 6.46179C16.5689 6.96579 16.7915 7.50305 16.9466 8.05862C17.0061 8.27194 17.1786 8.43491 17.3952 8.48206L18.8048 8.78845V11.2115Z"
      fill="black"/>
</svg>
                </span>
                    <span class="block w-[24px]">
                    <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M8.97012 16.4751H2.24251C1.82988 16.4751 1.49502 16.1402 1.49502 15.7276V2.27245C1.49502 1.85983 1.82992 1.52496 2.24251 1.52496H8.97012C9.38348 1.52496 9.71761 1.19084 9.71761 0.77747C9.71761 0.364103 9.38348 0.0299072 8.97012 0.0299072H2.24251C1.00614 0.0299072 0 1.03608 0 2.27245V15.7276C0 16.964 1.00614 17.9701 2.24251 17.9701H8.97012C9.38348 17.9701 9.71761 17.636 9.71761 17.2226C9.71761 16.8092 9.38348 16.4751 8.97012 16.4751Z"
      fill="black"/>
<path d="M17.7772 8.46778L13.2323 3.98272C12.9393 3.69268 12.4654 3.69644 12.1753 3.99021C11.8853 4.28397 11.8883 4.75714 12.1828 5.04718L15.4307 8.25248H6.72747C6.31411 8.25248 5.97998 8.58661 5.97998 8.99997C5.97998 9.41334 6.31411 9.7475 6.72747 9.7475H15.4307L12.1828 12.9528C11.8883 13.2428 11.8861 13.716 12.1753 14.0098C12.3218 14.1578 12.5147 14.2325 12.7076 14.2325C12.8974 14.2325 13.0873 14.1608 13.2323 14.0172L17.7772 9.53217C17.9192 9.39165 17.9999 9.20026 17.9999 8.99994C17.9999 8.79969 17.9199 8.60907 17.7772 8.46778Z"
      fill="black"/>
</svg>
                </span>
                </div>
            </div>
        </div>

        <div class="w-full mx-auto gap-4 p-6 bg-cyan-500 items-center h-[155px]">
            <div class="container">
                <div class="w-11/12 mx-auto flex">
                    <div class="w-40 h-40 rounded-lg overflow-hidden border-2 border-white top-[10px]">
                        <img src="/assets/img/user.jpg" alt="User Avatar" class="w-full h-full"/>
                    </div>
                    <div class="w-[220px] ml-8 top-[50px]">
                        <h2 class="text-4xl font-semibold text-white">John Doe</h2>
                        <p class="text-white text-opacity-75">Last online: 2 days ago</p>
                    </div>
                    <div class="w-auto items-end top-[50px]">
                        <div class=" flex gap-4 items-end">
                            <button class="px-4 py-2 bg-white text-cyan-500 rounded-lg shadow hover:bg-gray-100 send-button">
                                <i class="fa-solid fa-paper-plane pr-1"></i> Send Message
                            </button>
                            <button class="px-4 py-2 bg-white text-cyan-500 rounded-lg shadow hover:bg-gray-100 add-button">
                                <i class="fa-solid fa-plus pr-1"></i>
                                Add Friend
                            </button>
                        </div>
                    </div>
                </div>

            </div>


        </div>


        <!-- Refresh Button -->

        <!-- Table Section -->
        <div class="container p-6">
            <div className="w-11/12 mx-auto flex justify-end mt-3">
                <button @click="refreshUsers" class="bg-blue-500 text-white px-4 py-2 rounded-lg mb-4">
                    Refresh
                </button>
            </div>
            <table class="w-11/12 mx-auto">
                <thead>
                <tr class="text-left bg-gray-100">
                    <th class="p-4 border-b">Date</th>
                    <th class="p-4 border-b">Name</th>
                    <th class="p-4 border-b">Gender</th>
                    <th class="p-4 border-b">Country</th>
                    <th class="p-4 border-b">Email</th>
                </tr>
                </thead>
                <!-- Loader (Display while data is being fetched) -->
                <tr colspan="4" v-if="loading">
                    <td></td>
                    <td></td>
                    <td colspan="4" class="flex justify-center items-center py-4">
                        <div class="flex items-center">
                            <svg
                                    class="animate-spin h-6 w-6 text-blue-500"
                                    xmlns="http://www.w3.org/2000/svg"
                                    fill="none"
                                    viewBox="0 0 24 24"
                                    stroke="currentColor"
                            >
                                <circle
                                        cx="12"
                                        cy="12"
                                        r="10"
                                        stroke-width="4"
                                        class="opacity-25"
                                />
                                <path
                                        fill="none"
                                        stroke-width="4"
                                        d="M4 12a8 8 0 1 1 16 0A8 8 0 0 1 4 12z"
                                        class="opacity-75"
                                />
                            </svg>
                            <span class="ml-2 text-gray-600">Loading...</span>
                        </div>
                    </td>
                </tr>

                <tbody v-if="!loading">
                <tr
                        v-for="user in sortedUsers"
                        :key="user.id"
                        @click="openUserDetail(user)"
                        class="my-row px-4 py-5 cursor-pointer hover:bg-gray-50 shadow-md rounded-lg hover:border hover:border-cyan-500 hover:rounded-lg gap-y-4"
                >
                    <td class="p-4 text-gray-500 table-td-p">
                        {{ formatDate(user.registered.date) }}
                    </td>
                    <td class="p-4 font-semibold text-black-600 table-td-p name">
                        {{ user.name.first }} {{ user.name.last }}
                    </td>
                    <td class="p-4 text-gray-500 table-td-p gender">{{ formatGender(user.gender) }}</td>
                    <td class="p-4 text-black-500 table-td-p">{{ user.location.country }}</td>
                    <td class="p-4 text-gray-500 table-td-p">{{ user.email }}</td>
                </tr>
                </tbody>
            </table>

            <!-- Pagination Controls -->
            <div class="w-11/12 mx-auto flex justify-between items-center mt-5">
                <div>
                    <!-- Pagination Text -->
                    <span class="text-gray-600">
            Showing {{ (page - 1) * pageSize + 1 }} -
            {{ Math.min(page * pageSize, totalRecords) }} of {{ totalRecords }}
          </span>
                </div>
                <div>
                    <button
                            @click="goToPage(page - 1)"
                            :disabled="page <= 1"
                            class="px-4 py-2 bg-cyan-500 text-white rounded-lg shadow hover:bg-white hover:text-cyan-500"
                    >
                        Previous
                    </button>
                    <span class="mx-2">Page {{ page }}</span>
                    <button
                            @click="goToPage(page + 1)"
                            :disabled="page * pageSize >= totalRecords"
                            class="px-4 py-2 bg-cyan-500 text-white rounded-lg shadow hover:bg-white hover:text-cyan-500"
                    >
                        Next
                    </button>
                </div>
                <div>
                    <label for="pageSize" class="mr-2">Items per page:</label>
                    <select
                            v-model="pageSize"
                            @change="fetchUsers"
                            id="pageSize"
                            class="border p-2 rounded-md"
                    >
                        <option v-for="size in [5, 10, 20]" :key="size" :value="size">
                            {{ size }}
                        </option>
                    </select>
                </div>
            </div>
        </div>
    </div>

    <!-- User Detail Modal -->
    <UserDetailModal
            v-if="selectedUser"
            :user="selectedUser"
            @close="closeModal"
    />
</template>

<script>
    import axios from 'axios';
    import UserDetailModal from '../components/UserDetailModal.vue';

    export default {
        components: {UserDetailModal},
        data() {
            return {
                users: [],
                sortBy: 'name',
                sortDirection: 'asc',
                selectedUser: null,
                page: 1,
                pageSize: 20,
                totalRecords: 200, // Fixed total number of records
                recordsLoaded: 0, // Track total records loaded so far
                loading: false,
            };
        },
        computed: {
            sortedUsers() {
                return [...this.users].sort((a, b) => {
                    if (a[this.sortBy] < b[this.sortBy])
                        return this.sortDirection === 'asc' ? -1 : 1;
                    if (a[this.sortBy] > b[this.sortBy])
                        return this.sortDirection === 'asc' ? 1 : -1;
                    return 0;
                });
            },
        },
        methods: {
            async fetchUsers() {
                // Stop fetching if recordsLoaded has reached the totalRecords limit
                if (this.recordsLoaded >= this.totalRecords) return;

                this.loading = true; // Set loading to true when API call starts
                try {
                    const response = await axios.get('https://randomuser.me/api/', {
                        params: {
                            results: this.pageSize,
                            page: this.page,
                            seed: 'abc',
                        },
                    });
                    this.users = response.data.results;

                    // Update recordsLoaded based on fetched results
                    this.recordsLoaded += this.users.length;
                } catch (error) {
                    console.error('Error fetching users:', error);
                } finally {
                    this.loading = false; // Set loading to false when the API call finishes
                }
            },
            setSort(column) {
                if (this.sortBy === column) {
                    this.sortDirection = this.sortDirection === 'asc' ? 'desc' : 'asc';
                } else {
                    this.sortBy = column;
                    this.sortDirection = 'asc';
                }
            },
            openUserDetail(user) {
                this.selectedUser = user;
            },
            closeModal() {
                this.selectedUser = null;
            },
            goToPage(pageNumber) {
                if (
                    pageNumber >= 1 &&
                    (pageNumber - 1) * this.pageSize < this.totalRecords
                ) {
                    this.page = pageNumber;
                    this.fetchUsers();
                }
            },
            refreshUsers() {
                this.page = 1;
                this.recordsLoaded = 0; // Reset records loaded on refresh
                this.fetchUsers();
            },
            formatGender(gender) {
                return gender.charAt(0).toUpperCase() + gender.slice(1);
            },
            formatDate(dateString) {
                const date = new Date(dateString);
                const options = {year: 'numeric', month: 'short', day: 'numeric'};
                return date.toLocaleDateString('en-GB', options);
            },
        },
        mounted() {
            this.fetchUsers();
        },
    };
</script>

<style scoped>
    .my-row:hover .name {
        color: #0891B2
    }
    .my-row:hover .gender {
        color: #000000
    }
</style>