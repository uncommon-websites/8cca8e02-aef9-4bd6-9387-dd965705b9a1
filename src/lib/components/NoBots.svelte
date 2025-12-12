<script lang="ts">
  // No Bots Section
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid md:grid-cols-2 gap-16 items-center">
      <div>
        <h2 class="text-3xl font-bold mb-6">No more tool-switching fatigue</h2>
        <p class="text-gray-600 mb-8">
          Stop juggling between Notion for notes, Calendly for bookings, QuickBooks for invoices, and email for follow-ups. TAAARS! brings everything together in one connected workspace:
        </p>
        
        <ul class="space-y-4">
          {#each ['Client info syncs across projects, invoices, and bookings', 'Proposals automatically generate invoices when accepted', 'Payment reminders send without you lifting a finger', 'Everything you need in one place, nothing you don\'t'] as item}
            <li class="flex items-start gap-3">
              <div class="w-5 h-5 rounded-full bg-green-100 flex items-center justify-center mt-0.5 shrink-0">
                <svg class="w-3 h-3 text-green-600" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" />
                </svg>
              </div>
              <span class="text-gray-700 text-sm">{item}</span>
            </li>
          {/each}
        </ul>
      </div>
      
      <div class="relative">
        <!-- Workflow Visualization -->
        <div class="bg-gradient-to-br from-blue-50 to-purple-50 rounded-2xl p-8 shadow-lg">
           <div class="bg-white rounded-xl overflow-hidden shadow-2xl p-6">
              <div class="text-center mb-6">
                <h4 class="font-bold text-gray-900 mb-2">Connected Workflow</h4>
                <p class="text-xs text-gray-500">Everything flows together automatically</p>
              </div>
              
              <!-- Workflow Steps -->
              <div class="space-y-3">
                <div class="flex items-center gap-3 p-3 bg-green-50 rounded-lg border border-green-200">
                  <div class="w-8 h-8 rounded-full bg-green-500 text-white flex items-center justify-center text-sm font-bold shrink-0">1</div>
                  <div class="text-sm">
                    <div class="font-medium text-gray-900">New Client Added</div>
                    <div class="text-xs text-gray-600">Contact info saved once</div>
                  </div>
                </div>
                
                <div class="flex items-center justify-center">
                  <svg class="w-4 h-4 text-gray-300" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                  </svg>
                </div>
                
                <div class="flex items-center gap-3 p-3 bg-blue-50 rounded-lg border border-blue-200">
                  <div class="w-8 h-8 rounded-full bg-blue-500 text-white flex items-center justify-center text-sm font-bold shrink-0">2</div>
                  <div class="text-sm">
                    <div class="font-medium text-gray-900">Proposal Sent</div>
                    <div class="text-xs text-gray-600">Client details auto-filled</div>
                  </div>
                </div>
                
                <div class="flex items-center justify-center">
                  <svg class="w-4 h-4 text-gray-300" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                  </svg>
                </div>
                
                <div class="flex items-center gap-3 p-3 bg-purple-50 rounded-lg border border-purple-200">
                  <div class="w-8 h-8 rounded-full bg-purple-500 text-white flex items-center justify-center text-sm font-bold shrink-0">3</div>
                  <div class="text-sm">
                    <div class="font-medium text-gray-900">Invoice Generated</div>
                    <div class="text-xs text-gray-600">When proposal accepted</div>
                  </div>
                </div>
                
                <div class="flex items-center justify-center">
                  <svg class="w-4 h-4 text-gray-300" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                  </svg>
                </div>
                
                <div class="flex items-center gap-3 p-3 bg-yellow-50 rounded-lg border border-yellow-200">
                  <div class="w-8 h-8 rounded-full bg-yellow-500 text-white flex items-center justify-center text-sm font-bold shrink-0">4</div>
                  <div class="text-sm">
                    <div class="font-medium text-gray-900">Payment Received</div>
                    <div class="text-xs text-gray-600">Auto-reminders sent</div>
                  </div>
                </div>
              </div>
           </div>
        </div>
        <p class="text-xs text-gray-500 mt-4 text-center">
          No manual data entry. No copy-pasting. Everything just works together.
        </p>
      </div>
    </div>
    
    <div class="mt-16 p-6 bg-green-50 rounded-xl border border-green-100">
      <p class="text-sm text-green-800">
        <span class="font-bold">I consolidated my entire system from sticky notes, voice memos, and random Google Docs into TAAARS!</span> Now I actually look forward to client onboarding instead of dreading the admin work.
      </p>
      <div class="mt-2 text-xs text-green-600 font-medium">Naomi • Executive Coach</div>
    </div>
  </div>
</section>
