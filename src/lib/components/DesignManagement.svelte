<script>
</script>

<section class="bg-[#2563EB] text-white py-24 overflow-hidden relative">
  <!-- Background gradient effect -->
  <div class="absolute inset-0 bg-gradient-to-b from-[#3B82F6] to-[#1D4ED8] opacity-100"></div>
  
  <div class="relative max-w-[1200px] mx-auto px-6 text-center">
    <h2 class="text-5xl font-bold mb-6 tracking-tight leading-tight">
      Unified Infrastructure<br>Orchestration
    </h2>
    <p class="text-blue-100 text-lg max-w-2xl mx-auto mb-16 leading-relaxed">
      A centralized control plane purpose-built for distributed cloud resources. Symfon IO lets you automate, coordinate, and govern every workflow decision — without fragmented tooling, manual handoffs, or configuration drift getting in the way.
    </p>

    <!-- UI Mockup -->
    <div class="bg-white rounded-xl shadow-2xl overflow-hidden text-left text-gray-900 mx-auto max-w-[1000px] border border-blue-400/30">
      <!-- Window Controls -->
      <div class="bg-gray-50 border-b border-gray-200 px-4 py-3 flex items-center gap-2">
        <div class="flex gap-1.5">
          <div class="w-3 h-3 rounded-full bg-red-400"></div>
          <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
          <div class="w-3 h-3 rounded-full bg-green-400"></div>
        </div>
        <div class="ml-4 flex items-center gap-2 text-xs font-medium text-gray-600 bg-white px-2 py-1 rounded border border-gray-200 shadow-sm">
           <span class="w-3 h-3 bg-gray-800 rounded-full flex items-center justify-center text-[8px] text-white">S</span>
           Symfon IO
           <span class="text-gray-400">▼</span>
        </div>
      </div>

      <div class="flex h-[500px]">
        <!-- Sidebar -->
        <div class="w-48 bg-gray-50 border-r border-gray-200 p-3 flex flex-col gap-1">
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">🕒</span> Recently run
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-900 bg-white shadow-sm border border-gray-200 rounded cursor-pointer">
            <span class="opacity-70">📦</span> Your workflows
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">🧩</span> Pipelines
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">⚙️</span> Resources
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">⚡</span> Connectors
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">📂</span> All workflows
          </div>
          
          <div class="mt-auto text-[10px] text-gray-400 px-2">88 workflows</div>
        </div>

        <!-- Main List -->
        <div class="flex-1 bg-white flex flex-col">
          <div class="border-b border-gray-100 p-3">
             <div class="relative">
                <span class="absolute left-2 top-1.5 text-gray-400 text-xs">🔍</span>
                <input type="text" placeholder="Search workflows and resources..." class="w-full bg-gray-50 border border-gray-200 rounded pl-7 pr-3 py-1 text-xs focus:outline-none focus:border-blue-500">
             </div>
          </div>
          <div class="flex-1 overflow-y-auto">
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">PR</div>
                   <span class="text-xs font-medium text-gray-700">Provision Cluster</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-blue-500">v6-13 · wf-1793</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 bg-blue-50/50 cursor-pointer">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-blue-100 text-blue-600 rounded flex items-center justify-center text-[8px]">DA</div>
                   <span class="text-xs font-medium text-gray-900">Deploy Automation</span>
                </div>
                <div class="text-[10px] text-gray-400">wf-8231</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">SC</div>
                   <span class="text-xs font-medium text-gray-700">Scale Controller Pipeline</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-blue-500">v9 · wf-3327</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">RH</div>
                   <span class="text-xs font-medium text-gray-700">Resource Health Check</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-blue-500">v2 · wf-2684</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">DR</div>
                   <span class="text-xs font-medium text-gray-700">Disaster Recovery Job</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-blue-500">wf-1924</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">SY</div>
                   <span class="text-xs font-medium text-gray-700">Sync State Agent</span>
                </div>
             </div>
          </div>
        </div>

        <!-- Right Panel -->
        <div class="w-80 bg-white border-l border-gray-200 flex flex-col">
          <div class="p-3 border-b border-gray-100 flex justify-between items-center">
             <span class="text-[10px] font-bold text-gray-400 uppercase tracking-wider">Run Detail</span>
             <button class="text-[10px] border border-gray-200 rounded px-2 py-1 hover:bg-gray-50 flex items-center gap-1">
                <span>👤</span> Take over as owner
             </button>
          </div>
          
          <div class="p-4 flex-1 overflow-y-auto">
             <div class="text-[10px] font-bold text-gray-400 uppercase tracking-wider mb-2">Select version to load</div>
             
             <!-- Version Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-gray-200">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-orange-400"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-900">Local changes</span>
                   <span class="text-[10px] text-gray-400">Saved 3 days ago</span>
                </div>
             </div>

             <!-- Version Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-blue-500">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-blue-500"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-900">Latest (fd649cb5)</span>
                   <span class="text-[10px] text-gray-400">Maya Okafor</span>
                </div>
                <div class="text-[10px] text-gray-600 mb-2">
                   Resolving connector timeout issues flagged during high-concurrency stress test on staging environment
                </div>
                <span class="inline-block px-1.5 py-0.5 bg-blue-100 text-blue-700 text-[9px] rounded font-medium">Current Commit</span>
             </div>

             <div class="flex items-center gap-2 mb-4 pl-4">
                <div class="w-1 h-1 bg-gray-300 rounded-full"></div>
                <div class="w-1 h-1 bg-gray-300 rounded-full"></div>
                <div class="w-1 h-1 bg-gray-300 rounded-full"></div>
                <span class="text-[10px] text-gray-400">Show 12 more commits</span>
             </div>

             <!-- Version Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-gray-200">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-gray-300"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-500">Revision 6</span>
                   <span class="text-[10px] text-gray-400">Dani Reeves</span>
                </div>
                <div class="text-[10px] text-gray-500">
                   Retry logic on the provisioning step was not accounting for transient network failures in multi-region deployments
                </div>
             </div>
             
             <!-- Version Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-gray-200">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-gray-300"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-500">Revision 5</span>
                   <span class="text-[10px] text-gray-400">Dani Reeves</span>
                </div>
                <div class="text-[10px] text-gray-500">
                   Adding modular agent configuration for secondary cloud regions and refining concurrency limits across distributed nodes.
                </div>
             </div>
          </div>
          
          <div class="p-3 border-t border-gray-100 bg-gray-50 flex justify-between items-center">
             <div class="flex items-center gap-2 text-[10px] text-gray-500">
                <button class="hover:text-gray-900">✕</button>
                <span>Do not load dependencies</span>
             </div>
             <div class="flex gap-2">
                <button class="bg-white border border-gray-200 text-gray-700 text-[10px] px-2 py-1 rounded hover:bg-gray-50">View on Symfon IO</button>
                <button class="bg-blue-600 text-white text-[10px] px-2 py-1 rounded hover:bg-blue-700">Open</button>
             </div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Bottom Logos -->
    <div class="mt-12 flex items-center justify-center gap-4 bg-[#1E293B] rounded-lg p-4 max-w-4xl mx-auto border border-gray-700">
       <div class="flex items-center gap-4 border-r border-gray-600 pr-4">
          <div class="w-8 h-8 bg-white rounded flex items-center justify-center font-bold text-black text-xs">TF</div>
          <div class="w-8 h-8 bg-red-600 rounded flex items-center justify-center font-bold text-white text-xs">K8</div>
          <div class="w-8 h-8 bg-yellow-600 rounded flex items-center justify-center font-bold text-black text-xs">GH</div>
       </div>
       <p class="text-xs text-gray-400 text-left flex-1">
          Symfon IO integrates seamlessly with your existing stack right out of the box. Manage workflows, commit changes, and orchestrate resources across cloud providers directly from Terraform, Kubernetes, or GitHub Actions.
       </p>
       <button class="bg-[#2563EB] text-white px-3 py-1.5 rounded text-xs font-semibold hover:bg-blue-600">Get started</button>
    </div>
  </div>
</section>