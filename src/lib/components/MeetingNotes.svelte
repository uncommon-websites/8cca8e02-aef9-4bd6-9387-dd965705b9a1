<script lang="ts">
  // Meeting Notes Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-green-600 font-medium">Client Management</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-4">From first contact to final payment</h2>
  
  <div class="flex gap-4 text-sm text-gray-500 mb-12 items-center">
    <span class="font-medium text-gray-900">Replaces:</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-orange-500"></div> HoneyBook</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-blue-500"></div> Dubsado</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-green-500"></div> Bonsai</span>
  </div>

  <div class="grid md:grid-cols-2 gap-16 mb-20">
    <div>
      <h3 class="font-bold text-lg mb-4">Why TAAARS!?</h3>
      <p class="text-gray-600 mb-4 leading-relaxed">
        Most business management tools are built for enterprises. They're bloated with features you'll never use and require hours of setup.
      </p>
      <p class="text-gray-600 leading-relaxed">
        TAAARS! is different. Built specifically for solopreneurs and small teams, with great defaults that work right out of the box. No user manual needed—you'll feel like you've been using it for years from day one.
      </p>
    </div>
    
    <div class="space-y-8">
      <!-- Testimonial 1 -->
      <div class="bg-gray-50 p-6 rounded-2xl relative">
        <div class="flex text-orange-400 mb-2">★★★★★</div>
        <div class="flex items-center gap-3 mb-3">
          <div class="w-8 h-8 bg-gray-300 rounded-full"></div>
          <div>
            <div class="font-bold text-sm">Brandon</div>
            <div class="text-xs text-gray-500">Consultant</div>
          </div>
        </div>
        <p class="text-sm text-gray-700">
          Replaced Notion, ClickUp, and Bonsai with TAAARS!. I actually enjoy admin days now—everything's in one place and just works together seamlessly.
        </p>
        <div class="absolute top-4 right-4 w-6 h-6 bg-purple-900 rounded-md"></div>
      </div>

       <!-- Testimonial 2 -->
       <div class="bg-gray-50 p-6 rounded-2xl relative">
        <div class="flex text-orange-400 mb-2">★★★★★</div>
        <div class="flex items-center gap-3 mb-3">
          <div class="w-8 h-8 bg-gray-300 rounded-full"></div>
          <div>
            <div class="font-bold text-sm">Lina</div>
            <div class="text-xs text-gray-500">Business Coach</div>
          </div>
        </div>
        <p class="text-sm text-gray-700">
          No more Sunday admin work! TAAARS! automated my invoice organization and client follow-ups. I've recovered hours every week that I can spend with actual clients.
        </p>
        <div class="absolute top-4 right-4 w-6 h-6 bg-pink-600 rounded-md"></div>
      </div>
    </div>
  </div>

  <div class="max-w-3xl mb-12">
    <h3 class="font-bold text-lg mb-4">Connected Workspace Architecture</h3>
    <p class="text-gray-600 mb-4 leading-relaxed">
      When your tools don't talk to each other, things fall through the cracks. Invoices get delayed. Client details get lost. Follow-ups are forgotten. TAAARS! connects everything—from your first client conversation to receiving payment.
    </p>
    <p class="text-gray-600 leading-relaxed">
      Create a project, and the client's contact info is already there. Send a proposal, and it automatically generates an invoice when accepted. Complete a milestone, and payment reminders go out automatically. Everything flows together.
    </p>
  </div>

  <!-- Large Interface Image -->
  <div class="w-full bg-gray-900 rounded-2xl overflow-hidden shadow-2xl border border-gray-800 pt-2 md:pt-8 px-2 md:px-8 pb-0">
    <!-- Feature Tabs (Dark Header) -->
    <div class="flex justify-center gap-8 mb-6 text-sm font-medium text-gray-400">
      <div class="flex items-center gap-2 hover:text-white cursor-pointer transition-colors">
        <div class="w-4 h-4 rounded-full border border-gray-600"></div>
        Clients
      </div>
      <div class="flex items-center gap-2 text-white cursor-pointer">
        <div class="w-4 h-4 rounded-full bg-white text-gray-900 flex items-center justify-center text-[10px]">✨</div>
        Projects
      </div>
      <div class="flex items-center gap-2 hover:text-white cursor-pointer transition-colors">
        <div class="w-4 h-4 rounded-full border border-gray-600"></div>
        Invoices
      </div>
    </div>

    <!-- App Window -->
    <div class="bg-white rounded-t-lg overflow-hidden h-[500px] flex flex-col shadow-2xl relative">
       <!-- Header -->
       <div class="border-b border-gray-100 p-4 flex justify-between items-center bg-white z-10">
         <div class="flex items-center gap-3">
           <div class="w-8 h-8 bg-green-100 rounded-lg flex items-center justify-center text-green-600 text-lg">📋</div>
           <div class="font-bold text-gray-900">Active Projects</div>
         </div>
         <div class="flex items-center gap-3">
           <button class="text-xs font-medium text-gray-500 hover:text-gray-700">Filter</button>
           <button class="bg-gray-900 text-white px-3 py-1.5 rounded-md text-xs font-medium">+ New Project</button>
         </div>
       </div>

       <!-- Content Area -->
       <div class="flex-1 overflow-y-auto bg-white p-6 md:p-8">
         <div class="space-y-4">
           <!-- Project Card 1 -->
           <div class="border border-gray-200 rounded-lg p-4 hover:shadow-md transition-shadow">
             <div class="flex items-start justify-between mb-3">
               <div>
                 <h4 class="font-bold text-gray-900 mb-1">Brand Strategy Project</h4>
                 <div class="text-sm text-gray-600">Sarah Martinez</div>
               </div>
               <span class="text-xs bg-green-100 text-green-700 px-2 py-1 rounded-full font-medium">Active</span>
             </div>
             <div class="flex gap-6 text-sm mb-3">
               <div>
                 <span class="text-gray-500">Value:</span>
                 <span class="font-medium ml-1">$4,500</span>
               </div>
               <div>
                 <span class="text-gray-500">Due:</span>
                 <span class="font-medium ml-1">Mar 15</span>
               </div>
               <div>
                 <span class="text-gray-500">Progress:</span>
                 <span class="font-medium ml-1">60%</span>
               </div>
             </div>
             <div class="flex gap-2">
               <button class="text-xs bg-gray-100 text-gray-700 px-3 py-1 rounded hover:bg-gray-200">View Details</button>
               <button class="text-xs bg-gray-100 text-gray-700 px-3 py-1 rounded hover:bg-gray-200">Send Invoice</button>
             </div>
           </div>

           <!-- Project Card 2 -->
           <div class="border border-gray-200 rounded-lg p-4 hover:shadow-md transition-shadow">
             <div class="flex items-start justify-between mb-3">
               <div>
                 <h4 class="font-bold text-gray-900 mb-1">Website Redesign</h4>
                 <div class="text-sm text-gray-600">Tech Startup Inc</div>
               </div>
               <span class="text-xs bg-blue-100 text-blue-700 px-2 py-1 rounded-full font-medium">In Progress</span>
             </div>
             <div class="flex gap-6 text-sm mb-3">
               <div>
                 <span class="text-gray-500">Value:</span>
                 <span class="font-medium ml-1">$8,200</span>
               </div>
               <div>
                 <span class="text-gray-500">Due:</span>
                 <span class="font-medium ml-1">Apr 1</span>
               </div>
               <div>
                 <span class="text-gray-500">Progress:</span>
                 <span class="font-medium ml-1">35%</span>
               </div>
             </div>
             <div class="flex gap-2">
               <button class="text-xs bg-gray-100 text-gray-700 px-3 py-1 rounded hover:bg-gray-200">View Details</button>
               <button class="text-xs bg-gray-100 text-gray-700 px-3 py-1 rounded hover:bg-gray-200">Update Progress</button>
             </div>
           </div>

           <!-- Project Card 3 -->
           <div class="border border-gray-200 rounded-lg p-4 hover:shadow-md transition-shadow">
             <div class="flex items-start justify-between mb-3">
               <div>
                 <h4 class="font-bold text-gray-900 mb-1">Marketing Strategy</h4>
                 <div class="text-sm text-gray-600">Local Bakery</div>
               </div>
               <span class="text-xs bg-yellow-100 text-yellow-700 px-2 py-1 rounded-full font-medium">Proposal Sent</span>
             </div>
             <div class="flex gap-6 text-sm mb-3">
               <div>
                 <span class="text-gray-500">Value:</span>
                 <span class="font-medium ml-1">$2,800</span>
               </div>
               <div>
                 <span class="text-gray-500">Sent:</span>
                 <span class="font-medium ml-1">2 days ago</span>
               </div>
             </div>
             <div class="flex gap-2">
               <button class="text-xs bg-gray-100 text-gray-700 px-3 py-1 rounded hover:bg-gray-200">Follow Up</button>
               <button class="text-xs bg-gray-100 text-gray-700 px-3 py-1 rounded hover:bg-gray-200">View Proposal</button>
             </div>
           </div>
         </div>
       </div>
    </div>
  </div>

  <!-- Features Grid -->
  <div class="mt-12 grid md:grid-cols-3 gap-6 text-center text-sm">
    <div>
      <div class="text-2xl mb-2">📝</div>
      <div class="font-bold mb-1">Unlimited Everything</div>
      <div class="text-gray-600">Contacts, projects, invoices, forms, bookings, agreements—no limits</div>
    </div>
    <div>
      <div class="text-2xl mb-2">⚡</div>
      <div class="font-bold mb-1">Blazing Fast Support</div>
      <div class="text-gray-600">Get help when you need it at help@taaars.com</div>
    </div>
    <div>
      <div class="text-2xl mb-2">🔄</div>
      <div class="font-bold mb-1">30-Day Free Trial</div>
      <div class="text-gray-600">No credit card required. Cancel anytime</div>
    </div>
  </div>
</section>
