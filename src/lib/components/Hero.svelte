<script lang="ts">
  // Hero Section
</script>

<section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto flex flex-col items-center text-center">
  <h1 class="text-5xl md:text-7xl font-bold tracking-tight text-gray-900 max-w-4xl mb-8 leading-[1.1]">
    Your admin life, <span class="italic">made easy</span>
  </h1>
  
  <p class="text-xl text-gray-600 max-w-2xl mb-12">
    One platform. Zero overwhelm. Everything you need to run your service business—from client onboarding to getting paid.
  </p>

  <div class="flex flex-col sm:flex-row gap-4 mb-16">
    <button class="bg-gray-900 text-white px-8 py-3 rounded-full text-lg font-medium hover:bg-gray-800 transition-colors">
      Start free trial
    </button>
    <button class="bg-white text-gray-900 border border-gray-200 px-8 py-3 rounded-full text-lg font-medium hover:bg-gray-50 transition-colors flex items-center gap-2">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-play-circle"><circle cx="12" cy="12" r="10"/><polygon points="10 8 16 12 10 16 10 8"/></svg>
      Watch demo
    </button>
  </div>

  <!-- Hero Image Placeholder (App Interface) -->
  <div class="w-full max-w-5xl bg-white rounded-xl shadow-2xl border border-gray-200 overflow-hidden relative aspect-[16/10] text-left">
    <!-- Fake Browser Header -->
    <div class="bg-gray-50 border-b border-gray-200 p-3 flex items-center gap-2">
      <div class="flex gap-1.5">
        <div class="w-3 h-3 rounded-full bg-red-400"></div>
        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
        <div class="w-3 h-3 rounded-full bg-green-400"></div>
      </div>
      <div class="mx-auto text-xs text-gray-400 font-medium">Sarah Martinez - Brand Strategy Project</div>
    </div>
    
    <!-- App Content -->
    <div class="flex h-full">
      <!-- Sidebar -->
      <div class="w-64 border-r border-gray-100 bg-gray-50/50 p-4 hidden md:block">
        <div class="space-y-4">
          <div class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-2">Clients</div>
          <div class="space-y-2">
             <div class="h-8 w-full bg-white border border-gray-200 rounded-lg shadow-sm flex items-center px-3 text-xs font-medium">
               <div class="w-2 h-2 rounded-full bg-green-500 mr-2"></div>
               Sarah Martinez
             </div>
             <div class="h-8 w-full bg-transparent rounded-lg flex items-center px-3 text-xs text-gray-600">
               <div class="w-2 h-2 rounded-full bg-blue-500 mr-2"></div>
               Tech Startup Inc
             </div>
             <div class="h-8 w-full bg-transparent rounded-lg flex items-center px-3 text-xs text-gray-600">
               <div class="w-2 h-2 rounded-full bg-yellow-500 mr-2"></div>
               Local Bakery
             </div>
          </div>
          <div class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-2 mt-6">Quick Actions</div>
          <div class="space-y-1 text-xs text-gray-600">
            <div class="py-1">+ New Invoice</div>
            <div class="py-1">+ New Project</div>
            <div class="py-1">+ Book Meeting</div>
          </div>
        </div>
      </div>
      
      <!-- Main Content -->
      <div class="flex-1 p-8 bg-white">
        <div class="max-w-3xl mx-auto">
           <div class="flex items-center justify-between mb-6">
             <h2 class="text-2xl font-bold">Brand Strategy Project</h2>
             <span class="text-xs bg-green-100 text-green-700 px-3 py-1 rounded-full font-medium">Active</span>
           </div>
           
           <div class="space-y-6 text-sm">
             <div class="flex gap-8">
               <div>
                 <div class="text-xs text-gray-500 mb-1">Client</div>
                 <div class="font-medium">Sarah Martinez</div>
               </div>
               <div>
                 <div class="text-xs text-gray-500 mb-1">Project Value</div>
                 <div class="font-medium">$4,500</div>
               </div>
               <div>
                 <div class="text-xs text-gray-500 mb-1">Due Date</div>
                 <div class="font-medium">Mar 15, 2025</div>
               </div>
             </div>

             <div class="border-t border-gray-100 pt-6">
               <h3 class="font-bold mb-3">Project Tasks</h3>
               <div class="space-y-2">
                 <div class="flex items-center gap-3 p-2 bg-gray-50 rounded">
                   <div class="w-4 h-4 border-2 border-green-500 rounded bg-green-500 flex items-center justify-center">
                     <svg class="w-3 h-3 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                       <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" />
                     </svg>
                   </div>
                   <span class="text-gray-500 line-through">Initial consultation & discovery</span>
                 </div>
                 <div class="flex items-center gap-3 p-2">
                   <div class="w-4 h-4 border-2 border-gray-300 rounded"></div>
                   <span class="text-gray-900">Brand positioning workshop</span>
                   <span class="ml-auto text-xs text-gray-400">Tomorrow</span>
                 </div>
                 <div class="flex items-center gap-3 p-2">
                   <div class="w-4 h-4 border-2 border-gray-300 rounded"></div>
                   <span class="text-gray-900">Draft brand guidelines</span>
                 </div>
               </div>
             </div>

             <div class="border-t border-gray-100 pt-6">
               <div class="flex justify-between items-center mb-3">
                 <h3 class="font-bold">Invoices</h3>
                 <button class="text-xs text-gray-600 hover:text-gray-900">+ Create Invoice</button>
               </div>
               <div class="flex items-center justify-between p-3 bg-green-50 rounded border border-green-100">
                 <div>
                   <div class="font-medium text-sm">Invoice #001 - Deposit</div>
                   <div class="text-xs text-gray-600">$1,500 • Paid Jan 15</div>
                 </div>
                 <div class="text-xs font-medium text-green-700">PAID</div>
               </div>
             </div>
           </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Replaces Section -->
  <div class="mt-20 relative w-full max-w-5xl">
    <p class="text-sm text-gray-500 mb-6 text-center">Replaces your patchwork of tools</p>
    <div class="flex flex-wrap justify-center items-center gap-6 md:gap-12 opacity-40 grayscale text-sm md:text-base">
       <span class="font-semibold">HoneyBook</span>
       <span class="font-semibold">Dubsado</span>
       <span class="font-semibold">Bonsai</span>
       <span class="font-semibold">Notion</span>
       <span class="font-semibold">ClickUp</span>
       <span class="font-semibold">Calendly</span>
       <span class="font-semibold">QuickBooks</span>
    </div>
    
    <!-- Stats -->
    <div class="mt-16 grid grid-cols-3 gap-8 text-center">
      <div>
        <div class="text-3xl font-bold text-gray-900 mb-1">5+</div>
        <div class="text-sm text-gray-500">Tools replaced</div>
      </div>
      <div>
        <div class="text-3xl font-bold text-gray-900 mb-1">30%</div>
        <div class="text-sm text-gray-500">More repeat clients</div>
      </div>
      <div>
        <div class="text-3xl font-bold text-gray-900 mb-1">2x</div>
        <div class="text-sm text-gray-500">Faster payments</div>
      </div>
    </div>
  </div>
</section>
