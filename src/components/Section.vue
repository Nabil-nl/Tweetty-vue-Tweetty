<template>
    <main
        class="flex justify-center mt-[-1rem]  w-[552px] max-w-screen-lg ml-[33.4rem] border-r border-[#bdbdbd] shadow-lg z-50">
        <!-- Middle -->
        <div class="w-[550px] h-[47.5rem]  ">
            <!-- Header -->
            <div class="flex justify-between items-center border-b px-4 py-3 sticky top-0 bg-white dark:bg-dim-900">
                <!-- Title -->
                <h2 class="text-gray-800 dark:text-black font-bold font-sm">Home</h2>
                <!-- /Title -->

                <!-- Custom Timeline -->
                <div>
                    <svg viewBox="0 0 24 24" class="w-5 h-5 text-blue-400" fill="currentColor">
                        <g>
                            <path
                                d="M22.772 10.506l-5.618-2.192-2.16-6.5c-.102-.307-.39-.514-.712-.514s-.61.207-.712.513l-2.16 6.5-5.62 2.192c-.287.112-.477.39-.477.7s.19.585.478.698l5.62 2.192 2.16 6.5c.102.306.39.513.712.513s.61-.207.712-.513l2.16-6.5 5.62-2.192c.287-.112.477-.39.477-.7s-.19-.585-.478-.697zm-6.49 2.32c-.208.08-.37.25-.44.46l-1.56 4.695-1.56-4.693c-.07-.21-.23-.38-.438-.462l-4.155-1.62 4.154-1.622c.208-.08.37-.25.44-.462l1.56-4.693 1.56 4.694c.07.212.23.382.438.463l4.155 1.62-4.155 1.622zM6.663 3.812h-1.88V2.05c0-.414-.337-.75-.75-.75s-.75.336-.75.75v1.762H1.5c-.414 0-.75.336-.75.75s.336.75.75.75h1.782v1.762c0 .414.336.75.75.75s.75-.336.75-.75V5.312h1.88c.415 0 .75-.336.75-.75s-.335-.75-.75-.75zm2.535 15.622h-1.1v-1.016c0-.414-.335-.75-.75-.75s-.75.336-.75.75v1.016H5.57c-.414 0-.75.336-.75.75s.336.75.75.75H6.6v1.016c0 .414.335.75.75.75s.75-.336.75-.75v-1.016h1.098c.414 0 .75-.336.75-.75s-.336-.75-.75-.75z">
                            </path>
                        </g>
                    </svg>
                </div>
                <!-- /Custom Timeline -->
            </div>
            <!-- /Header -->

            <!-- Post Tweet -->
            <div class="border border-gray-200 dark:border-dim-200 pb-4">
                <div class="flex flex-shrink-0 p-4 pb-0">
                    <div class="w-12 flex items-top">
                        <img class="inline-block h-10 w-10 rounded-full" src="@/assets/images/n.png" alt="Image 1">
                    </div>
                    <div class="w-full p-2">
                        <textarea
                            class="dark:text-black text-gray-900 placeholder-gray-400 w-full h-10 bg-transparent border-0 focus:outline-none resize-none"
                            placeholder="What's happening?" v-model="newTweetContent"></textarea>
                    </div>
                </div>
                <div class="w-full flex items-top p-2 text-white pl-14">
                    <a href="#" class="text-[#1DA1F2] hover:bg-blue-50 dark:hover:bg-dim-800 rounded-full p-2">
                        <svg viewBox="0 0 24 24" class="w-5 h-5" fill="currentColor">
                            <g>
                                <path
                                    d="M19.75 2H4.25C3.01 2 2 3.01 2 4.25v15.5C2 20.99 3.01 22 4.25 22h15.5c1.24 0 2.25-1.01 2.25-2.25V4.25C22 3.01 20.99 2 19.75 2zM4.25 3.5h15.5c.413 0 .75.337.75.75v9.676l-3.858-3.858c-.14-.14-.33-.22-.53-.22h-.003c-.2 0-.393.08-.532.224l-4.317 4.384-1.813-1.806c-.14-.14-.33-.22-.53-.22-.193-.03-.395.08-.535.227L3.5 17.642V4.25c0-.413.337-.75.75-.75zm-.744 16.28l5.418-5.534 6.282 6.254H4.25c-.402 0-.727-.322-.744-.72zm16.244.72h-2.42l-5.007-4.987 3.792-3.85 4.385 4.384v3.703c0 .413-.337.75-.75.75z">
                                </path>
                                <circle cx="8.868" cy="8.309" r="1.542"></circle>
                            </g>
                        </svg>
                    </a>

                    <a href="#" class="text-[#1DA1F2] hover:bg-blue-50 dark:hover:bg-dim-800 rounded-full p-2">
                        <svg viewBox="0 0 24 24" class="w-5 h-5" fill="currentColor">
                            <g>
                                <path
                                    d="M19 10.5V8.8h-4.4v6.4h1.7v-2h2v-1.7h-2v-1H19zm-7.3-1.7h1.7v6.4h-1.7V8.8zm-3.6 1.6c.4 0 .9.2 1.2.5l1.2-1C9.9 9.2 9 8.8 8.1 8.8c-1.8 0-3.2 1.4-3.2 3.2s1.4 3.2 3.2 3.2c1 0 1.8-.4 2.4-1.1v-2.5H7.7v1.2h1.2v.6c-.2.1-.5.2-.8.2-.9 0-1.6-.7-1.6-1.6 0-.8.7-1.6 1.6-1.6z">
                                </path>
                                <path
                                    d="M20.5 2.02h-17c-1.24 0-2.25 1.007-2.25 2.247v15.507c0 1.238 1.01 2.246 2.25 2.246h17c1.24 0 2.25-1.008 2.25-2.246V4.267c0-1.24-1.01-2.247-2.25-2.247zm.75 17.754c0 .41-.336.746-.75.746h-17c-.414 0-.75-.336-.75-.746V4.267c0-.412.336-.747.75-.747h17c.414 0 .75.335.75.747v15.507z">
                                </path>
                            </g>
                        </svg>
                    </a>

                    <a href="#" class="text-[#1DA1F2] hover:bg-blue-50 dark:hover:bg-dim-800 rounded-full p-2">
                        <svg viewBox="0 0 24 24" class="w-5 h-5" fill="currentColor">
                            <g>
                                <path
                                    d="M20.222 9.16h-1.334c.015-.09.028-.182.028-.277V6.57c0-.98-.797-1.777-1.778-1.777H3.5V3.358c0-.414-.336-.75-.75-.75s-.75.336-.75.75V20.83c0 .415.336.75.75.75s.75-.335.75-.75v-1.434h10.556c.98 0 1.778-.797 1.778-1.777v-2.313c0-.095-.014-.187-.028-.278h4.417c.98 0 1.778-.798 1.778-1.778v-2.31c0-.983-.797-1.78-1.778-1.78zM17.14 6.293c.152 0 .277.124.277.277v2.31c0 .154-.125.28-.278.28H3.5V6.29h13.64zm-2.807 9.014v2.312c0 .153-.125.277-.278.277H3.5v-2.868h10.556c.153 0 .277.126.277.28zM20.5 13.25c0 .153-.125.277-.278.277H3.5V10.66h16.722c.153 0 .278.124.278.277v2.313z">
                                </path>
                            </g>
                        </svg>
                    </a>

                    <a href="#" class="text-[#1DA1F2] hover:bg-blue-50 dark:hover:bg-dim-800 rounded-full p-2">
                        <svg viewBox="0 0 24 24" class="w-5 h-5" fill="currentColor">
                            <g>
                                <path
                                    d="M12 22.75C6.072 22.75 1.25 17.928 1.25 12S6.072 1.25 12 1.25 22.75 6.072 22.75 12 17.928 22.75 12 22.75zm0-20C6.9 2.75 2.75 6.9 2.75 12S6.9 21.25 12 21.25s9.25-4.15 9.25-9.25S17.1 2.75 12 2.75z">
                                </path>
                                <path
                                    d="M12 17.115c-1.892 0-3.633-.95-4.656-2.544-.224-.348-.123-.81.226-1.035.348-.226.812-.124 1.036.226.747 1.162 2.016 1.855 3.395 1.855s2.648-.693 3.396-1.854c.224-.35.688-.45 1.036-.225.35.224.45.688.226 1.036-1.025 1.594-2.766 2.545-4.658 2.545z">
                                </path>
                                <circle cx="14.738" cy="9.458" r="1.478"></circle>
                                <circle cx="9.262" cy="9.458" r="1.478"></circle>
                            </g>
                        </svg>
                    </a>

                    <a href="#" class="text-[#1DA1F2] hover:bg-blue-50 dark:hover:bg-dim-800 rounded-full p-2">
                        <svg viewBox="0 0 24 24" class="w-5 h-5" fill="currentColor">
                            <g>
                                <path d="M-37.9 18c-.1-.1-.1-.1-.1-.2.1 0 .1.1.1.2z"></path>
                                <path
                                    d="M-37.9 18c-.1-.1-.1-.1-.1-.2.1 0 .1.1.1.2zM18 2.2h-1.3v-.3c0-.4-.3-.8-.8-.8-.4 0-.8.3-.8.8v.3H7.7v-.3c0-.4-.3-.8-.8-.8-.4 0-.8.3-.8.8v.3H4.8c-1.4 0-2.5 1.1-2.5 2.5v13.1c0 1.4 1.1 2.5 2.5 2.5h2.9c.4 0 .8-.3.8-.8 0-.4-.3-.8-.8-.8H4.8c-.6 0-1-.5-1-1V7.9c0-.3.4-.7 1-.7H18c.6 0 1 .4 1 .7v1.8c0 .4.3.8.8.8.4 0 .8-.3.8-.8v-5c-.1-1.4-1.2-2.5-2.6-2.5zm1 3.7c-.3-.1-.7-.2-1-.2H4.8c-.4 0-.7.1-1 .2V4.7c0-.6.5-1 1-1h1.3v.5c0 .4.3.8.8.8.4 0 .8-.3.8-.8v-.5h7.5v.5c0 .4.3.8.8.8.4 0 .8-.3.8-.8v-.5H18c.6 0 1 .5 1 1v1.2z">
                                </path>
                                <path
                                    d="M15.5 10.4c-3.4 0-6.2 2.8-6.2 6.2 0 3.4 2.8 6.2 6.2 6.2 3.4 0 6.2-2.8 6.2-6.2 0-3.4-2.8-6.2-6.2-6.2zm0 11c-2.6 0-4.7-2.1-4.7-4.7s2.1-4.7 4.7-4.7 4.7 2.1 4.7 4.7c0 2.5-2.1 4.7-4.7 4.7z">
                                </path>
                                <path
                                    d="M18.9 18.7c-.1.2-.4.4-.6.4-.1 0-.3 0-.4-.1l-3.1-2v-3c0-.4.3-.8.8-.8.4 0 .8.3.8.8v2.2l2.4 1.5c.2.2.3.6.1 1z">
                                </path>
                            </g>
                        </svg>
                    </a>

                    <a href="#" class="bg-[#1DA1F2] hover:bg-[#1DA1F2] text-white rounded-full py-1 px-4 ml-auto mr-1"
                        @click="postTweet">
                        <span class="font-bold text-sm">Tweet</span>
                    </a>
                </div>
            </div>
            <!-- Display Tweets -->
            <div class="mt-4">
                <div v-for="tweet in tweets" :key="tweet.id"
                    class="border-b border-gray-200 dark:border-dim-200 py-3 px-4">
                    <div class="flex items-center">
                        <!-- User Avatar -->
                        <img class="inline-block h-10 w-10 rounded-full" src="@/assets/images/n.png" alt="Image 1">

                        <!-- Tweet Content -->
                        <div class="ml-3 flex-1">
                            <h3 class="font-bold text-gray-800 dark:text-black">{{ tweet.user }}</h3>
                            <p class="text-gray-600 dark:text-gray-400">{{ tweet.content }}</p>
                        </div>
                    </div>

                    <!-- Action Icons Container (Centered) -->
                    <div class="flex justify-center mt-3 space-x-4">
                        <!-- Like Icon -->
                        <div>
                            <a @click="toggleLike(tweet.id)"
                                class="group flex items-center text-[#f72585] px-3 py-2 text-base leading-6 font-medium rounded-full hover:bg-[#f7f7f7] hover:text-[#f72585]">
                                <svg class="h-6 w-6" :class="{ 'text-blue-500': isLiked(tweet.id) }" fill="none"
                                    stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    stroke="currentColor" viewBox="0 0 24 24">
                                    <path
                                        d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z">
                                    </path>
                                </svg>
                                <span class="ml-2">{{ tweet.likes }}</span>
                            </a>
                        </div>

                        <!-- Retweet Icon -->
                        <div>
                            <a @click="retweet(tweet.id)"
                                class="group flex items-center text-[#35ff69] px-3 py-2 text-base leading-6 font-medium rounded-full hover:bg-[#f7f7f7] hover:text-[#35ff69]">
                                <svg class="h-6 w-6" fill="none" stroke-linecap="round" stroke-linejoin="round"
                                    stroke-width="2" stroke="currentColor" viewBox="0 0 24 24">
                                    <path d="M7 16V4m0 0L3 8m4-4l4 4m6 0v12m0 0l4-4m-4 4l-4-4"></path>
                                </svg>
                                <span class="ml-2">{{ tweet.retweets }}</span>
                            </a>
                        </div>

                        <!-- Response Icon -->
                        <div>
                            <a @click="respond(tweet.id)" class="group flex items-center text-[#01baef] px-3 py-2 text-base leading-6 font-medium rounded-full hover:bg-[#f7f7f7] hover:text-[#01baef]">
                                <svg class="h-6 w-6" fill="none" stroke-linecap="round" stroke-linejoin="round"
                                    stroke-width="2" stroke="currentColor" viewBox="0 0 24 24">
                                    <path
                                        d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z">
                                    </path>
                                </svg>
                                <span class="ml-2">{{ tweet.responses }}</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>


        </div>
    </main>
</template>


<script>
import axios from 'axios';

export default {
    name: "Section",
    data() {
        return {
            tweets: [],
            users: [],
            newTweetContent: "",
            likedTweets: [] // Track liked tweets
        };
    },
    created() {
        this.fetchTweets();
        this.fetchUsers();
    },
    methods: {
        fetchTweets() {
            axios.get('http://localhost:3000/tweets')
                .then(response => {
                    this.tweets = response.data;
                })
                .catch(error => {
                    console.error("There was an error fetching the tweets:", error);
                });
        },
        fetchUsers() {
            axios.get('http://localhost:3000/users')
                .then(response => {
                    this.users = response.data;
                })
                .catch(error => {
                    console.error("There was an error fetching the users:", error);
                });
        },
        getUserProfileImage(username) {
            const user = this.users.find(user => user.username === username);
            return user ? user.profile_image : '@/assets/images/default_profile.jpg';
        },
        postTweet() {
            if (this.newTweetContent.trim() !== "") {
                const newTweet = {
                    id: (this.tweets.length + 1).toString(),
                    user: "TTT",
                    content: this.newTweetContent,
                    likes: 0,
                    retweets: 0,
                    responses: 0
                };
                axios.post('http://localhost:3000/tweets', newTweet)
                    .then(response => {
                        this.tweets.unshift(response.data);
                        this.newTweetContent = "";
                    })
                    .catch(error => {
                        console.error("There was an error posting the tweet:", error);
                    });
            }
        },
        toggleLike(tweetId) {
            const tweet = this.tweets.find(t => t.id === tweetId);
            if (!tweet) return;

            if (this.isLiked(tweetId)) {
                tweet.likes--;
                this.likedTweets = this.likedTweets.filter(id => id !== tweetId);
            } else {
                tweet.likes++;
                this.likedTweets.push(tweetId);
            }

            // Update the tweet likes on the server
            axios.put(`http://localhost:3000/tweets/${tweetId}`, tweet)
                .catch(error => {
                    console.error("There was an error updating the tweet:", error);
                });
        },
        isLiked(tweetId) {
            return this.likedTweets.includes(tweetId);
        },
        retweet(tweetId) {
            const tweet = this.tweets.find(t => t.id === tweetId);
            if (!tweet) return;

            tweet.retweets++;

            // Update the tweet retweets on the server
            axios.put(`http://localhost:3000/tweets/${tweetId}`, tweet)
                .catch(error => {
                    console.error("There was an error updating the tweet:", error);
                });
        },
        respond(tweetId) {
            const tweet = this.tweets.find(t => t.id === tweetId);
            if (!tweet) return;

            tweet.responses++;

            // Update the tweet responses on the server
            axios.put(`http://localhost:3000/tweets/${tweetId}`, tweet)
                .catch(error => {
                    console.error("There was an error updating the tweet:", error);
                });
        }
    }
};
</script>

<style scoped></style>
