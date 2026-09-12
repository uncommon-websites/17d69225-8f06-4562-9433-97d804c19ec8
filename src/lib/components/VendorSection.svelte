<script>
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-[1200px] mx-auto px-6">
    <div class="text-center mb-16">
      <h2 class="text-5xl font-bold mb-6 tracking-tight text-gray-900 leading-tight">
        Bring Your<br>Partners In
      </h2>
      <p class="text-lg text-gray-600 max-w-2xl mx-auto leading-relaxed">
        Configurations shared with external teams never fall through the cracks with Symfon IO. Replace scattered handoffs with a solution that's secure, auditable, and effortless.
      </p>
    </div>

    <!-- File Sharing UI -->
    <img src="/generated/image-a-secure-modern-workspace-with-two-engin-1789240205726-0.webp" alt="Secure cloud config sharing" class="w-full h-[300px] object-cover rounded-xl shadow-xl mb-8 max-w-4xl mx-auto border border-gray-200" />
       <!-- Mockup content -->
       <div class="flex h-[400px]">
          <!-- File List -->
          <div class="flex-1 p-6">
             <div class="flex items-center justify-between mb-6">
                <div class="flex items-center gap-2">
                   <div class="w-8 h-8 bg-gray-100 rounded flex items-center justify-center">📄</div>
                   <div>
                      <div class="text-xs font-bold text-gray-900">prod-cluster-us-east-1.tf</div>
                      <div class="text-[10px] text-gray-400">1.2 MB</div>
                   </div>
                </div>
             </div>
             
             <div class="bg-yellow-50 border border-yellow-100 rounded-lg p-3 mb-6 text-xs text-gray-700 flex gap-2">
                <span>📝</span>
                Note the custom ingress controller config required for multi-region failover — see the annotated block near the load balancer definition.
             </div>
             
             <div class="space-y-3">
                <div class="flex items-center justify-between p-2 hover:bg-gray-50 rounded cursor-pointer">
                   <div class="flex items-center gap-2">
                      <span class="text-gray-400">📄</span>
                      <span class="text-xs text-gray-600">prod-cluster-us-east-1.tf</span>
                   </div>
                   <span class="text-[10px] text-gray-400">68 MB</span>
                </div>
                <div class="flex items-center justify-between p-2 hover:bg-gray-50 rounded cursor-pointer">
                   <div class="flex items-center gap-2">
                      <span class="text-gray-400">📄</span>
                      <span class="text-xs text-gray-600">prod-cluster-us-east-1.yaml</span>
                   </div>
                   <span class="text-[10px] text-gray-400">32 MB</span>
                </div>
                <div class="flex items-center justify-between p-2 hover:bg-gray-50 rounded cursor-pointer">
                   <div class="flex items-center gap-2">
                      <span class="text-gray-400">📄</span>
                      <span class="text-xs text-gray-600">staging-cluster-eu-west-2.tf</span>
                   </div>
                   <span class="text-[10px] text-gray-400">31 MB</span>
                </div>
                <div class="flex items-center justify-between p-2 hover:bg-gray-50 rounded cursor-pointer">
                   <div class="flex items-center gap-2">
                      <span class="text-gray-400">📄</span>
                      <span class="text-xs text-gray-600">staging-cluster-eu-west-2.yaml</span>
                   </div>
                   <span class="text-[10px] text-gray-400">12 MB</span>
                </div>
             </div>
             
             <div class="mt-8 text-[10px] text-gray-400">5 files • 144MB</div>
          </div>
          
          <!-- Package Details -->
          <div class="w-72 bg-gray-50 border-l border-gray-200 p-6 flex flex-col">
             <h3 class="font-bold text-sm text-gray-900 mb-4">Production Rollout Config Bundle</h3>
             
             <div class="flex items-center gap-2 mb-4">
                <div class="w-6 h-6 bg-red-500 rounded-full text-white flex items-center justify-center text-[10px] font-bold">P</div>
                <div>
                   <div class="text-xs font-bold text-gray-900">Peter Gandolfini</div>
                   <div class="text-[10px] text-gray-500">Platform Engineer at Symfon IO · 8d</div>
                </div>
             </div>
             
             <div class="flex items-center gap-2 text-xs text-gray-500 mb-6">
                <span>⏰</span> Expires in 7 days
             </div>
             
             <p class="text-xs text-gray-600 mb-6 leading-relaxed">
                Here's the packaged config bundle for the production cluster rollout. As discussed, we're targeting a zero-downtime migration for the us-east-1 region first before expanding to EU.
             </p>
             
             <button class="mt-auto bg-[#2563EB] text-white w-full py-2 rounded text-xs font-bold hover:bg-blue-600 flex items-center justify-center gap-2">
                <span>⬇️</span> Download
             </button>
          </div>
       </div>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <!-- Provider Access Control -->
      <div class="bg-gradient-to-br from-[#8B3A75] to-[#6B2A55] rounded-xl p-8 text-white h-[300px] relative overflow-hidden">
         <h3 class="text-lg font-bold mb-2">Provider Access Control</h3>
         <p class="text-pink-100 text-xs mb-6 max-w-xs">
            Grant multiple cloud providers and integration partners access to the same control plane — each sees only the resources and workflows assigned to them.
         </p>
         
         <!-- Mini Table UI -->
         <div class="bg-white rounded-lg shadow-lg p-2 text-gray-900 text-[8px] absolute bottom-0 left-4 right-4 translate-y-10 hover:translate-y-0 transition-transform duration-300">
            <div class="grid grid-cols-4 font-bold text-gray-400 mb-2 border-b border-gray-100 pb-1">
               <div>STATUS</div>
               <div>LATENCY</div>
               <div>CON.</div>
               <div>PROVIDER</div>
            </div>
            <div class="space-y-2">
               <div class="grid grid-cols-4 items-center">
                  <div class="text-green-600 bg-green-50 px-1 py-0.5 rounded w-fit">Active</div>
                  <div>3</div>
                  <div>1</div>
                  <div class="flex items-center gap-1"><div class="w-3 h-3 bg-red-100 rounded-full"></div> AWS</div>
               </div>
               <div class="grid grid-cols-4 items-center">
                  <div class="text-green-600 bg-green-50 px-1 py-0.5 rounded w-fit">Active</div>
                  <div>5</div>
                  <div>1</div>
                  <div class="flex items-center gap-1"><div class="w-3 h-3 bg-blue-100 rounded-full"></div> GCP...</div>
               </div>
               <div class="grid grid-cols-4 items-center">
                  <div class="text-green-600 bg-green-50 px-1 py-0.5 rounded w-fit">Active</div>
                  <div>1</div>
                  <div>1</div>
                  <div class="flex items-center gap-1"><div class="w-3 h-3 bg-yellow-100 rounded-full"></div> Azure...</div>
               </div>
               <div class="grid grid-cols-4 items-center">
                  <div class="text-green-600 bg-green-50 px-1 py-0.5 rounded w-fit">Active</div>
                  <div>1</div>
                  <div>1</div>
                  <div class="flex items-center gap-1"><div class="w-3 h-3 bg-green-100 rounded-full"></div> AWS</div>
               </div>
            </div>
         </div>
      </div>

      <!-- Structured Permissions -->
      <div class="md:col-span-2 bg-gradient-to-br from-[#C28E2B] to-[#A6761D] rounded-xl p-8 text-white h-[300px] relative overflow-hidden">
         <h3 class="text-lg font-bold mb-2">Structured Permissions for External Teams</h3>
         <p class="text-yellow-100 text-xs mb-6 max-w-md">
            Invite multiple teams from the same partner organization and assign each of them granular permissions for the workflows, environments, and resources they need within Symfon IO.
         </p>
         
         <!-- Permissions UI -->
         <div class="bg-white rounded-lg shadow-lg p-4 text-gray-900 absolute bottom-6 left-8 right-8">
            <div class="space-y-3">
               <div class="flex items-center justify-between border-b border-gray-100 pb-2">
                  <div class="flex items-center gap-3">
                     <div class="w-8 h-8 bg-gray-200 rounded-full"></div>
                     <div>
                        <div class="text-xs font-bold">Nexara Platform Engineers</div>
                        <div class="text-[10px] text-gray-400">Access group for Nexara</div>
                     </div>
                  </div>
                  <div class="flex gap-2">
                     <button class="text-[10px] border border-gray-200 rounded px-2 py-1 flex items-center gap-1">✏️ Edit access</button>
                     <button class="text-[10px] border border-gray-200 rounded px-2 py-1">Invite people</button>
                  </div>
               </div>
               
               <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3 pl-4">
                     <div class="w-6 h-6 bg-purple-500 rounded-full"></div>
                     <div>
                        <div class="text-xs font-bold">Harmon Wilkerson</div>
                        <div class="text-[10px] text-gray-400">Head of Infrastructure · mailto:harmon@nexara.io</div>
                     </div>
                  </div>
                  <div class="text-[10px] text-gray-500">Nexara ⋮</div>
               </div>

               <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3 pl-4">
                     <div class="w-6 h-6 bg-pink-500 rounded-full"></div>
                     <div>
                        <div class="text-xs font-bold">Martina Smena</div>
                        <div class="text-[10px] text-gray-400">DevOps Engineer · mailto:smena@nexara.io</div>
                     </div>
                  </div>
                  <div class="text-[10px] text-gray-500">Nexara ⋮</div>
               </div>
            </div>
         </div>
      </div>
    </div>
  </div>
</section>
