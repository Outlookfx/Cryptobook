
# Bloomfame>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloom - Women's Wellness</title>
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    <script>tailwind.config={theme:{extend:{colors:{primary:'#ff7eb6',secondary:'#7eb8ff'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
    <style>
        :where([class^="ri-"])::before { content: "\f3c2"; }
        body {
            font-family: 'Poppins', sans-serif;
            padding-bottom: 72px;
            padding-top: 64px;
        }
        .scroll-container {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
        .scroll-container::-webkit-scrollbar {
            display: none;
        }
    </style>
</head>
<body class="bg-white">
    <!-- Nav Bar -->
    <header class="fixed top-0 left-0 w-full bg-white shadow-sm z-50">
        <div class="flex items-center justify-between px-4 py-3">
            <h1 class="text-2xl font-['Pacifico'] text-primary">logo</h1>
            <div class="flex items-center space-x-3">
                <div class="w-8 h-8 flex items-center justify-center cursor-pointer">
                    <i class="ri-search-line ri-lg"></i>
                </div>
                <div class="w-8 h-8 flex items-center justify-center cursor-pointer">
                    <i class="ri-notification-3-line ri-lg"></i>
                </div>
            </div>
        </div>
    </header>
    <!-- Main Content -->
    <main class="px-4 py-4">
        <!-- Hero Section -->
        <section class="mb-6">
            <div class="relative rounded-xl overflow-hidden shadow-sm h-44 mb-4">
                <img src="https://readdy.ai/api/search-image?query=Soft%20gradient%20background%20with%20feminine%20wellness%20elements%2C%20lotus%20flowers%2C%20leaves%2C%20and%20gentle%20pastel%20colors%2C%20calming%20atmosphere%2C%20minimalist%20design%2C%20high%20quality%20illustration&width=375&height=176&seq=1&orientation=landscape" alt="Wellness Banner" class="w-full h-full object-cover">
                <div class="absolute inset-0 bg-gradient-to-r from-primary/70 to-transparent flex flex-col justify-center px-6">
                    <h2 class="text-white text-2xl font-semibold mb-1">Welcome to Your Wellness Journey</h2>
                    <p class="text-white text-sm opacity-90">Personalized care for every phase</p>
                </div>
            </div>
            
            <!-- Date Display -->
            <div class="flex items-center justify-between mb-5">
                <div>
                    <p class="text-gray-500 text-xs">Friday, June 6</p>
                    <h3 class="text-lg font-medium">Good morning, Olivia</h3>
                </div>
                <div class="bg-primary/10 px-3 py-1.5 rounded-full">
                    <p class="text-primary text-xs font-medium">Day 12 of cycle</p>
                </div>
            </div>
        </section>

        <!-- Quick Access Categories -->
        <section class="mb-8">
            <h3 class="text-lg font-medium mb-4">Explore Categories</h3>
            <div class="grid grid-cols-4 gap-3">
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-16 h-16 rounded-full overflow-hidden mb-2 shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20skincare%20products%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=64&height=64&seq=2&orientation=squarish" alt="Skincare" class="w-full h-full object-cover">
                    </div>
                    <span class="text-xs text-center font-medium whitespace-nowrap overflow-hidden text-overflow-ellipsis">Skincare</span>
                </div>
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-16 h-16 rounded-full overflow-hidden mb-2 shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20home%20self-care%20items%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=64&height=64&seq=3&orientation=squarish" alt="Home Routines" class="w-full h-full object-cover">
                    </div>
                    <span class="text-xs text-center font-medium whitespace-nowrap overflow-hidden text-overflow-ellipsis">Home Routines</span>
                </div>
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-16 h-16 rounded-full overflow-hidden mb-2 shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20healthy%20food%20and%20nutrition%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=64&height=64&seq=4&orientation=squarish" alt="Nutrition" class="w-full h-full object-cover">
                    </div>
                    <span class="text-xs text-center font-medium whitespace-nowrap overflow-hidden text-overflow-ellipsis">Nutrition</span>
                </div>
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-16 h-16 rounded-full overflow-hidden mb-2 shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20menstrual%20cycle%20and%20period%20care%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=64&height=64&seq=5&orientation=squarish" alt="Period Care" class="w-full h-full object-cover">
                    </div>
                    <span class="text-xs text-center font-medium whitespace-nowrap overflow-hidden text-overflow-ellipsis">Period Care</span>
                </div>
            </div>
        </section>

        <!-- Daily Wellness Tip -->
        <section class="mb-8">
            <div class="flex items-center justify-between mb-4">
                <h3 class="text-lg font-medium">Daily Wellness Tip</h3>
                <span class="text-primary text-xs font-medium cursor-pointer">View All</span>
            </div>
            <div class="bg-gradient-to-r from-primary/10 to-secondary/10 p-4 rounded-xl shadow-sm">
                <div class="flex items-start">
                    <div class="w-10 h-10 flex items-center justify-center bg-primary/20 rounded-full mr-3 flex-shrink-0">
                        <i class="ri-mental-health-line ri-lg text-primary"></i>
                    </div>
                    <div>
                        <h4 class="font-medium text-sm mb-1">Mindful Morning Ritual</h4>
                        <p class="text-xs text-gray-600 leading-relaxed">Start your day with 5 minutes of deep breathing before checking your phone. This helps reduce stress hormones and sets a positive tone for the day.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skincare Section -->
        <section class="mb-8">
            <div class="flex items-center justify-between mb-4">
                <h3 class="text-lg font-medium">Skincare Routines</h3>
                <span class="text-primary text-xs font-medium cursor-pointer">See All</span>
            </div>
            <div class="overflow-x-auto scroll-container -mx-4 px-4">
                <div class="flex space-x-4 w-max pb-2">
                    <div class="w-40 flex-shrink-0 cursor-pointer">
                        <div class="h-40 rounded-xl overflow-hidden mb-2 shadow-sm">
                            <img src="https://readdy.ai/api/search-image?query=Morning%20skincare%20routine%20products%20beautifully%20arranged%20on%20a%20clean%20white%20surface%2C%20soft%20natural%20lighting%2C%20minimalist%20aesthetic%2C%20high-quality%20product%20photography%2C%20skincare%20bottles%20and%20jars%2C%20pastel%20colors%2C%20clean%20and%20fresh%20look%2C%20professional%20beauty%20product%20styling&width=160&height=160&seq=6&orientation=squarish" alt="Morning Routine" class="w-full h-full object-cover">
                        </div>
                        <h4 class="font-medium text-sm">Morning Routine</h4>
                        <p class="text-xs text-gray-500">5 steps • 10 min</p>
                    </div>
                    <div class="w-40 flex-shrink-0 cursor-pointer">
                        <div class="h-40 rounded-xl overflow-hidden mb-2 shadow-sm">
                            <img src="https://readdy.ai/api/search-image?query=Evening%20skincare%20routine%20products%20beautifully%20arranged%20with%20soft%20ambient%20lighting%2C%20calming%20aesthetic%2C%20premium%20skincare%20bottles%20and%20containers%2C%20serums%20and%20night%20creams%2C%20elegant%20product%20photography%2C%20relaxing%20mood%2C%20high-end%20beauty%20products&width=160&height=160&seq=7&orientation=squarish" alt="Night Routine" class="w-full h-full object-cover">
                        </div>
                        <h4 class="font-medium text-sm">Night Routine</h4>
                        <p class="text-xs text-gray-500">6 steps • 15 min</p>
                    </div>
                    <div class="w-40 flex-shrink-0 cursor-pointer">
                        <div class="h-40 rounded-xl overflow-hidden mb-2 shadow-sm">
                            <img src="https://readdy.ai/api/search-image?query=Natural%20DIY%20face%20mask%20ingredients%2C%20fresh%20fruits%2C%20honey%2C%20yogurt%2C%20avocado%2C%20beautifully%20arranged%20on%20marble%20surface%2C%20soft%20natural%20lighting%2C%20homemade%20skincare%2C%20organic%20beauty%20treatments%2C%20clean%20aesthetic%2C%20fresh%20ingredients%20for%20facial%20care&width=160&height=160&seq=8&orientation=squarish" alt="DIY Masks" class="w-full h-full object-cover">
                        </div>
                        <h4 class="font-medium text-sm">DIY Face Masks</h4>
                        <p class="text-xs text-gray-500">8 recipes • Natural</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Home Routines Section -->
        <section class="mb-8">
            <div class="flex items-center justify-between mb-4">
                <h3 class="text-lg font-medium">Self-Care Practices</h3>
                <span class="text-primary text-xs font-medium cursor-pointer">See All</span>
            </div>
            <div class="grid grid-cols-2 gap-4">
                <div class="bg-white rounded-xl shadow-sm overflow-hidden cursor-pointer">
                    <div class="h-32 overflow-hidden">
                        <img src="https://readdy.ai/api/search-image?query=Woman%20meditating%20in%20a%20peaceful%20home%20environment%2C%20morning%20sunlight%2C%20minimalist%20interior%2C%20calm%20atmosphere%2C%20wellness%20and%20mindfulness%20practice%2C%20serene%20expression%2C%20comfortable%20casual%20clothing%2C%20self-care%20moment&width=160&height=128&seq=9&orientation=landscape" alt="Meditation" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3">
                        <h4 class="font-medium text-sm mb-1">Morning Meditation</h4>
                        <p class="text-xs text-gray-500">10 min • Beginner</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl shadow-sm overflow-hidden cursor-pointer">
                    <div class="h-32 overflow-hidden">
                        <img src="https://readdy.ai/api/search-image?query=Woman%20journaling%20in%20cozy%20home%20setting%2C%20cup%20of%20tea%20nearby%2C%20soft%20blanket%2C%20warm%20lighting%2C%20peaceful%20atmosphere%2C%20self-reflection%20moment%2C%20wellness%20activity%2C%20comfortable%20casual%20clothing&width=160&height=128&seq=10&orientation=landscape" alt="Journaling" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3">
                        <h4 class="font-medium text-sm mb-1">Gratitude Journal</h4>
                        <p class="text-xs text-gray-500">5 min • Daily practice</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl shadow-sm overflow-hidden cursor-pointer">
                    <div class="h-32 overflow-hidden">
                        <img src="https://readdy.ai/api/search-image?query=Woman%20doing%20gentle%20yoga%20stretches%20at%20home%2C%20morning%20light%2C%20comfortable%20yoga%20mat%2C%20peaceful%20expression%2C%20wellness%20routine%2C%20simple%20home%20setting%2C%20self-care%20activity%2C%20casual%20comfortable%20clothing&width=160&height=128&seq=11&orientation=landscape" alt="Yoga" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3">
                        <h4 class="font-medium text-sm mb-1">Gentle Morning Yoga</h4>
                        <p class="text-xs text-gray-500">15 min • Energizing</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl shadow-sm overflow-hidden cursor-pointer">
                    <div class="h-32 overflow-hidden">
                        <img src="https://readdy.ai/api/search-image?query=Woman%20enjoying%20relaxing%20bath%20with%20candles%2C%20bath%20salts%2C%20flowers%2C%20self-care%20ritual%2C%20peaceful%20bathroom%20setting%2C%20wellness%20moment%2C%20soft%20ambient%20lighting%2C%20calming%20atmosphere&width=160&height=128&seq=12&orientation=landscape" alt="Bath Ritual" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3">
                        <h4 class="font-medium text-sm mb-1">Evening Bath Ritual</h4>
                        <p class="text-xs text-gray-500">30 min • Relaxation</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Nutrition Section -->
        <section class="mb-8">
            <div class="flex items-center justify-between mb-4">
                <h3 class="text-lg font-medium">Nutrition Guide</h3>
                <span class="text-primary text-xs font-medium cursor-pointer">See All</span>
            </div>
            <div class="bg-white rounded-xl shadow-sm overflow-hidden mb-4">
                <div class="p-4">
                    <h4 class="font-medium text-base mb-3">Foods for Hormone Balance</h4>
                    <div class="space-y-3">
                        <div class="flex items-center">
                            <div class="w-10 h-10 rounded-full overflow-hidden mr-3 flex-shrink-0">
                                <img src="https://readdy.ai/api/search-image?query=Fresh%20avocados%2C%20high%20quality%20food%20photography%2C%20clean%20white%20background%2C%20healthy%20fats%2C%20nutritious%20food%2C%20detailed%20texture%2C%20professional%20lighting%2C%20single%20food%20item%20focus&width=40&height=40&seq=13&orientation=squarish" alt="Avocados" class="w-full h-full object-cover">
                            </div>
                            <div>
                                <h5 class="text-sm font-medium">Avocados</h5>
                                <p class="text-xs text-gray-500">Rich in healthy fats for hormone production</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-10 h-10 rounded-full overflow-hidden mr-3 flex-shrink-0">
                                <img src="https://readdy.ai/api/search-image?query=Fresh%20leafy%20greens%2C%20spinach%20and%20kale%2C%20high%20quality%20food%20photography%2C%20clean%20white%20background%2C%20nutritious%20vegetables%2C%20detailed%20texture%2C%20professional%20lighting%2C%20single%20food%20item%20focus&width=40&height=40&seq=14&orientation=squarish" alt="Leafy Greens" class="w-full h-full object-cover">
                            </div>
                            <div>
                                <h5 class="text-sm font-medium">Leafy Greens</h5>
                                <p class="text-xs text-gray-500">Support liver detoxification pathways</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-10 h-10 rounded-full overflow-hidden mr-3 flex-shrink-0">
                                <img src="https://readdy.ai/api/search-image?query=Fresh%20wild%20salmon%20fillet%2C%20high%20quality%20food%20photography%2C%20clean%20white%20background%2C%20omega-3%20rich%20food%2C%20nutritious%20protein%2C%20detailed%20texture%2C%20professional%20lighting%2C%20single%20food%20item%20focus&width=40&height=40&seq=15&orientation=squarish" alt="Wild Salmon" class="w-full h-full object-cover">
                            </div>
                            <div>
                                <h5 class="text-sm font-medium">Wild Salmon</h5>
                                <p class="text-xs text-gray-500">Omega-3s for reducing inflammation</p>
                            </div>
                        </div>
                    </div>
                    <button class="w-full mt-4 py-2 bg-primary/10 text-primary text-sm font-medium rounded-button cursor-pointer">View Full Guide</button>
                </div>
            </div>
            
            <div class="overflow-x-auto scroll-container -mx-4 px-4">
                <div class="flex space-x-4 w-max pb-2">
                    <div class="w-64 flex-shrink-0 bg-white rounded-xl shadow-sm overflow-hidden cursor-pointer">
                        <div class="h-40 overflow-hidden">
                            <img src="https://readdy.ai/api/search-image?query=Healthy%20breakfast%20bowl%20with%20yogurt%2C%20berries%2C%20seeds%2C%20and%20nuts%2C%20beautifully%20arranged%2C%20bright%20natural%20lighting%2C%20nutritious%20morning%20meal%2C%20fresh%20ingredients%2C%20vibrant%20colors%2C%20clean%20eating%2C%20high-quality%20food%20photography&width=256&height=160&seq=16&orientation=landscape" alt="Breakfast Bowl" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <h4 class="font-medium text-sm mb-1">Berry Protein Breakfast Bowl</h4>
                            <p class="text-xs text-gray-500">Perfect for follicular phase • 15 min prep</p>
                        </div>
                    </div>
                    <div class="w-64 flex-shrink-0 bg-white rounded-xl shadow-sm overflow-hidden cursor-pointer">
                        <div class="h-40 overflow-hidden">
                            <img src="https://readdy.ai/api/search-image?query=Healthy%20lunch%20salad%20with%20quinoa%2C%20roasted%20vegetables%2C%20avocado%2C%20and%20seeds%2C%20beautifully%20arranged%20in%20bowl%2C%20bright%20natural%20lighting%2C%20nutritious%20meal%2C%20fresh%20ingredients%2C%20vibrant%20colors%2C%20clean%20eating%2C%20high-quality%20food%20photography&width=256&height=160&seq=17&orientation=landscape" alt="Quinoa Salad" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <h4 class="font-medium text-sm mb-1">Nourishing Quinoa Power Salad</h4>
                            <p class="text-xs text-gray-500">Great for luteal phase • 20 min prep</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Period Tracking Section -->
        <section class="mb-8">
            <div class="flex items-center justify-between mb-4">
                <h3 class="text-lg font-medium">Cycle Tracking</h3>
                <span class="text-primary text-xs font-medium cursor-pointer">View Details</span>
            </div>
            <div class="bg-white rounded-xl shadow-sm overflow-hidden p-4">
                <div class="flex items-center justify-between mb-4">
                    <h4 class="font-medium">June 2025</h4>
                    <div class="flex space-x-2">
                        <div class="w-8 h-8 flex items-center justify-center rounded-full bg-gray-100 cursor-pointer">
                            <i class="ri-arrow-left-s-line"></i>
                        </div>
                        <div class="w-8 h-8 flex items-center justify-center rounded-full bg-gray-100 cursor-pointer">
                            <i class="ri-arrow-right-s-line"></i>
                        </div>
                    </div>
                </div>
                
                <div class="grid grid-cols-7 gap-1 mb-4">
                    <div class="text-center text-xs text-gray-500">S</div>
                    <div class="text-center text-xs text-gray-500">M</div>
                    <div class="text-center text-xs text-gray-500">T</div>
                    <div class="text-center text-xs text-gray-500">W</div>
                    <div class="text-center text-xs text-gray-500">T</div>
                    <div class="text-center text-xs text-gray-500">F</div>
                    <div class="text-center text-xs text-gray-500">S</div>
                </div>
                
                <div class="grid grid-cols-7 gap-1">
                    <!-- Week 1 -->
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">26</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">27</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">28</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">29</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">30</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">31</div>
                    <div class="h-8 flex items-center justify-center text-xs">1</div>
                    
                    <!-- Week 2 -->
                    <div class="h-8 flex items-center justify-center text-xs">2</div>
                    <div class="h-8 flex items-center justify-center text-xs">3</div>
                    <div class="h-8 flex items-center justify-center text-xs">4</div>
                    <div class="h-8 flex items-center justify-center text-xs">5</div>
                    <div class="h-8 flex items-center justify-center text-xs">6</div>
                    <div class="h-8 flex items-center justify-center text-xs bg-primary text-white rounded-full">7</div>
                    <div class="h-8 flex items-center justify-center text-xs">8</div>
                    
                    <!-- Week 3 -->
                    <div class="h-8 flex items-center justify-center text-xs">9</div>
                    <div class="h-8 flex items-center justify-center text-xs">10</div>
                    <div class="h-8 flex items-center justify-center text-xs">11</div>
                    <div class="h-8 flex items-center justify-center text-xs">12</div>
                    <div class="h-8 flex items-center justify-center text-xs">13</div>
                    <div class="h-8 flex items-center justify-center text-xs">14</div>
                    <div class="h-8 flex items-center justify-center text-xs">15</div>
                    
                    <!-- Week 4 -->
                    <div class="h-8 flex items-center justify-center text-xs">16</div>
                    <div class="h-8 flex items-center justify-center text-xs">17</div>
                    <div class="h-8 flex items-center justify-center text-xs">18</div>
                    <div class="h-8 flex items-center justify-center text-xs">19</div>
                    <div class="h-8 flex items-center justify-center text-xs">20</div>
                    <div class="h-8 flex items-center justify-center text-xs">21</div>
                    <div class="h-8 flex items-center justify-center text-xs">22</div>
                    
                    <!-- Week 5 -->
                    <div class="h-8 flex items-center justify-center text-xs">23</div>
                    <div class="h-8 flex items-center justify-center text-xs">24</div>
                    <div class="h-8 flex items-center justify-center text-xs">25</div>
                    <div class="h-8 flex items-center justify-center text-xs">26</div>
                    <div class="h-8 flex items-center justify-center text-xs">27</div>
                    <div class="h-8 flex items-center justify-center text-xs">28</div>
                    <div class="h-8 flex items-center justify-center text-xs">29</div>
                    
                    <!-- Week 6 -->
                    <div class="h-8 flex items-center justify-center text-xs">30</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">1</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">2</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">3</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">4</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">5</div>
                    <div class="h-8 flex items-center justify-center text-xs text-gray-400">6</div>
                </div>
                
                <div class="mt-4 flex items-center space-x-4">
                    <div class="flex items-center">
                        <div class="w-3 h-3 rounded-full bg-primary mr-2"></div>
                        <span class="text-xs">Period</span>
                    </div>
                    <div class="flex items-center">
                        <div class="w-3 h-3 rounded-full bg-secondary mr-2"></div>
                        <span class="text-xs">Fertile Window</span>
                    </div>
                    <div class="flex items-center">
                        <div class="w-3 h-3 rounded-full bg-green-400 mr-2"></div>
                        <span class="text-xs">Ovulation</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Newsletter Signup -->
        <section class="mb-8">
            <div class="bg-gradient-to-r from-primary/20 to-secondary/20 rounded-xl p-5 shadow-sm">
                <h3 class="text-lg font-medium mb-2">Join Our Community</h3>
                <p class="text-sm text-gray-600 mb-4">Get weekly wellness tips, cycle insights, and exclusive content.</p>
                <div class="flex flex-col space-y-3">
                    <input type="email" placeholder="Your email address" class="w-full px-4 py-3 rounded-button border-none shadow-sm text-sm">
                    <button class="w-full bg-primary text-white py-3 rounded-button font-medium text-sm shadow-sm cursor-pointer">Subscribe</button>
                </div>
            </div>
        </section>
    </main>

    <!-- Tab Bar -->
    <footer class="fixed bottom-0 left-0 w-full bg-white border-t border-gray-100 shadow-sm z-50">
        <div class="grid grid-cols-4 h-16">
            <div class="flex flex-col items-center justify-center cursor-pointer">
                <div class="w-6 h-6 flex items-center justify-center">
                    <i class="ri-home-5-fill ri-lg text-primary"></i>
                </div>
                <span class="text-xs mt-1 text-primary font-medium">Home</span>
            </div>
            <div class="flex flex-col items-center justify-center cursor-pointer">
                <div class="w-6 h-6 flex items-center justify-center">
                    <i class="ri-sun-line ri-lg text-gray-400"></i>
                </div>
                <span class="text-xs mt-1 text-gray-400">Skincare</span>
            </div>
            <div class="flex flex-col items-center justify-center cursor-pointer">
                <div class="w-6 h-6 flex items-center justify-center">
                    <i class="ri-heart-pulse-line ri-lg text-gray-400"></i>
                </div>
                <span class="text-xs mt-1 text-gray-400">Wellness</span>
            </div>
            <div class="flex flex-col items-center justify-center cursor-pointer">
                <div class="w-6 h-6 flex items-center justify-center">
                    <i class="ri-calendar-line ri-lg text-gray-400"></i>
                </div>
                <span class="text-xs mt-1 text-gray-400">Period</span>
            </div>
        </div>
    </footer>

    <!-- FAB Button -->
    <div class="fixed right-4 bottom-20 w-12 h-12 bg-primary rounded-full shadow-lg flex items-center justify-center cursor-pointer z-40">
        <i class="ri-add-fill ri-xl text-white"></i>
    </div>

    <!-- Scripts -->
    <script id="navigation-handler">
        document.addEventListener('DOMContentLoaded', function() {
            const tabItems = document.querySelectorAll('footer .flex.flex-col');
            
            tabItems.forEach(item => {
                item.addEventListener('click', function() {
                    // Reset all tabs
                    tabItems.forEach(tab => {
                        const icon = tab.querySelector('i');
                        const text = tab.querySelector('span');
                        
                        icon.classList.remove('text-primary');
                        icon.classList.add('text-gray-400');
                        
                        text.classList.remove('text-primary');
                        text.classList.add('text-gray-400');
                        text.classList.remove('font-medium');
                    });
                    
                    // Set active tab
                    const activeIcon = this.querySelector('i');
                    const activeText = this.querySelector('span');
                    
                    activeIcon.classList.remove('text-gray-400');
                    activeIcon.classList.add('text-primary');
                    
                    activeText.classList.remove('text-gray-400');
                    activeText.classList.add('text-primary');
                    activeText.classList.add('font-medium');
                });
            });
        });
    </script>

    <script id="newsletter-handler">
        document.addEventListener('DOMContentLoaded', function() {
            const emailInput = document.querySelector('input[type="email"]');
            const subscribeButton = document.querySelector('button');
            
            subscribeButton.addEventListener('click', function() {
                const email = emailInput.value.trim();
                
                if (!email) {
                    // Create toast notification
                    const toast = document.createElement('div');
                    toast.className = 'fixed top-16 left-1/2 transform -translate-x-1/2 bg-gray-800 text-white px-4 py-2 rounded-lg text-sm z-50';
                    toast.textContent = 'Please enter your email address';
                    document.body.appendChild(toast);
                    
                    // Remove toast after 3 seconds
                    setTimeout(() => {
                        toast.remove();
                    }, 3000);
                    return;
                }
                
                if (!isValidEmail(email)) {
                    // Create toast notification
                    const toast = document.createElement('div');
                    toast.className = 'fixed top-16 left-1/2 transform -translate-x-1/2 bg-gray-800 text-white px-4 py-2 rounded-lg text-sm z-50';
                    toast.textContent = 'Please enter a valid email address';
                    document.body.appendChild(toast);
                    
                    // Remove toast after 3 seconds
                    setTimeout(() => {
                        toast.remove();
                    }, 3000);
                    return;
                }
                
                // Success notification
                const toast = document.createElement('div');
                toast.className = 'fixed top-16 left-1/2 transform -translate-x-1/2 bg-green-600 text-white px-4 py-2 rounded-lg text-sm z-50';
                toast.textContent = 'Thanks for subscribing!';
                document.body.appendChild(toast);
                
                // Clear input
                emailInput.value = '';
                
                // Remove toast after 3 seconds
                setTimeout(() => {
                    toast.remove();
                }, 3000);
            });
            
            function isValidEmail(email) {
                const re = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
                return re.test(email);
            }
        });
    </script>
    <script id="fab-handler">
        document.addEventListener('DOMContentLoaded', function() {
            const fab = document.querySelector('.fixed.right-4.bottom-20');
            
            fab.addEventListener('click', function() {
                // Create modal
                const modalOverlay = document.createElement('div');
                modalOverlay.className = 'fixed inset-0 bg-black bg-opacity-50 z-50 flex items-end justify-center';
                
                const modalContent = document.createElement('div');
                modalContent.className = 'bg-white w-full max-w-md rounded-t-xl p-5 transform transition-transform duration-300 ease-out';
                modalContent.style.transform = 'translateY(100%)';
                
                // Modal header
                const modalHeader = document.createElement('div');
                modalHeader.className = 'flex items-center justify-between mb-4';
                
                const modalTitle = document.createElement('h3');
                modalTitle.className = 'text-lg font-medium';
                modalTitle.textContent = 'Track Your Wellness';
                
                const closeButton = document.createElement('button');
                closeButton.className = 'w-8 h-8 flex items-center justify-center rounded-full bg-gray-100';
                closeButton.innerHTML = '<i class="ri-close-line"></i>';
                
                modalHeader.appendChild(modalTitle);
                modalHeader.appendChild(closeButton);
                
                // Modal options
                const options = [
                    { icon: 'ri-water-flash-line', text: 'Log Water Intake', color: 'bg-blue-100 text-blue-600' },
                    { icon: 'ri-mental-health-line', text: 'Log Mood', color: 'bg-purple-100 text-purple-600' },
                    { icon: 'ri-heart-pulse-line', text: 'Log Symptoms', color: 'bg-red-100 text-red-600' },
                    { icon: 'ri-capsule-line', text: 'Log Medication', color: 'bg-green-100 text-green-600' }
                ];
                
                const optionsContainer = document.createElement('div');
                optionsContainer.className = 'space-y-3';
                
                options.forEach(option => {
                    const optionButton = document.createElement('div');
                    optionButton.className = 'flex items-center p-3 rounded-xl bg-gray-50 cursor-pointer';
                    
                    const iconContainer = document.createElement('div');
                    iconContainer.className = `w-10 h-10 ${option.color} rounded-full flex items-center justify-center mr-3`;
                    iconContainer.innerHTML = `<i class="${option.icon}"></i>`;
                    
                    const textContainer = document.createElement('div');
                    textContainer.textContent = option.text;
                    textContainer.className = 'text-sm font-medium';
                    
                    optionButton.appendChild(iconContainer);
                    optionButton.appendChild(textContainer);
                    optionsContainer.appendChild(optionButton);
                });
                
                // Assemble modal
                modalContent.appendChild(modalHeader);
                modalContent.appendChild(optionsContainer);
                modalOverlay.appendChild(modalContent);
                document.body.appendChild(modalOverlay);
                
                // Animate in
                setTimeout(() => {
                    modalContent.style.transform = 'translateY(0)';
                }, 10);
                
                // Close modal function
                const closeModal = () => {
                    modalContent.style.transform = 'translateY(100%)';
                    setTimeout(() => {
                        document.body.removeChild(modalOverlay);
                    }, 300);
                };
                
                // Close on button click
                closeButton.addEventListener('click', closeModal);
                
                // Close on overlay click
                modalOverlay.addEventListener('click', (e) => {
                    if (e.target === modalOverlay) {
                        closeModal();
                    }
                });
                
                // Close on option click
                const optionButtons = optionsContainer.querySelectorAll('.flex.items-center.p-3');
                optionButtons.forEach(button => {
                    button.addEventListener('click', closeModal);
                });
            });
        });
    </script>
</body>
</html> 
