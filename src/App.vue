<template>
    <!-- Schermata Mobile -->
    <div v-if="onMobile" class="flex h-screen w-screen flex-col items-center justify-center gap-5 bg-slate-900 p-5 text-white">
        <h1 class="text-center text-5xl">Tailwind Colors</h1>
        <h2 class="text-2xl italic">by Andrea Damiani</h2>
        <Icon icon="mdi:smartphone-off" class="text-9xl" />
        <h2 class="text-center text-3xl">This App is only available on large screens.</h2>
    </div>

    <main v-else class="flex h-screen xl:text-sm 2xl:text-base">
        <!-- Table -->
        <ShadeGrid>
            <div class="flex w-full items-center justify-center font-semibold">Value</div>
            <div class="flex w-full items-center justify-center font-semibold">50</div>
            <div class="flex w-full items-center justify-center font-semibold">100</div>
            <div class="flex w-full items-center justify-center font-semibold">200</div>
            <div class="flex w-full items-center justify-center font-semibold">300</div>
            <div class="flex w-full items-center justify-center font-semibold">400</div>
            <div class="flex w-full items-center justify-center font-semibold">500</div>
            <div class="flex w-full items-center justify-center font-semibold">600</div>
            <div class="flex w-full items-center justify-center font-semibold">700</div>
            <div class="flex w-full items-center justify-center font-semibold">800</div>
            <div class="flex w-full items-center justify-center font-semibold">900</div>
            <div class="flex w-full items-center justify-center font-semibold">950</div>
        </ShadeGrid>

        <!-- Slate -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Slate</span>
            <ColorSquare class="bg-slate-50" to-be-copied="#f8fafc">#f8fafc</ColorSquare>
            <ColorSquare class="bg-slate-100" to-be-copied="#f1f5f9">#f1f5f9</ColorSquare>
            <ColorSquare class="bg-slate-200" to-be-copied="#e2e8f0">#e2e8f0</ColorSquare>
            <ColorSquare class="bg-slate-300" to-be-copied="#cbd5e1">#cbd5e1</ColorSquare>
            <ColorSquare class="bg-slate-400" to-be-copied="#94a3b8">#94a3b8</ColorSquare>
            <ColorSquare class="bg-slate-500" to-be-copied="#64748b">#64748b</ColorSquare>
            <ColorSquare class="bg-slate-600" to-be-copied="#475569">#475569</ColorSquare>
            <ColorSquare class="bg-slate-700" to-be-copied="#334155">#334155</ColorSquare>
            <ColorSquare class="bg-slate-800" to-be-copied="#1e293b">#1e293b</ColorSquare>
            <ColorSquare class="bg-slate-900" to-be-copied="#0f172a">#0f172a</ColorSquare>
            <ColorSquare class="bg-slate-950" to-be-copied="#020617">#020617</ColorSquare>
        </ShadeGrid>

        <!-- Gray -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Gray</span>
            <ColorSquare class="bg-gray-50" to-be-copied="#f9fafb">#f9fafb</ColorSquare>
            <ColorSquare class="bg-gray-100" to-be-copied="#f3f4f6">#f3f4f6</ColorSquare>
            <ColorSquare class="bg-gray-200" to-be-copied="#e5e7eb">#e5e7eb</ColorSquare>
            <ColorSquare class="bg-gray-300" to-be-copied="#d1d5db">#d1d5db</ColorSquare>
            <ColorSquare class="bg-gray-400" to-be-copied="#9ca3af">#9ca3af</ColorSquare>
            <ColorSquare class="bg-gray-500" to-be-copied="#6b7280">#6b7280</ColorSquare>
            <ColorSquare class="bg-gray-600" to-be-copied="#4b5563">#4b5563</ColorSquare>
            <ColorSquare class="bg-gray-700" to-be-copied="#374151">#374151</ColorSquare>
            <ColorSquare class="bg-gray-800" to-be-copied="#1f2937">#1f2937</ColorSquare>
            <ColorSquare class="bg-gray-900" to-be-copied="#111827">#111827</ColorSquare>
            <ColorSquare class="bg-gray-950" to-be-copied="#030712">#030712</ColorSquare>
        </ShadeGrid>

        <!-- Zinc -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Zinc</span>
            <ColorSquare class="bg-zinc-50" to-be-copied="#fafafa">#fafafa</ColorSquare>
            <ColorSquare class="bg-zinc-100" to-be-copied="#f4f4f5">#f4f4f5</ColorSquare>
            <ColorSquare class="bg-zinc-200" to-be-copied="#e4e4e7">#e4e4e7</ColorSquare>
            <ColorSquare class="bg-zinc-300" to-be-copied="#d4d4d8">#d4d4d8</ColorSquare>
            <ColorSquare class="bg-zinc-400" to-be-copied="#a1a1aa">#a1a1aa</ColorSquare>
            <ColorSquare class="bg-zinc-500" to-be-copied="#71717a">#71717a</ColorSquare>
            <ColorSquare class="bg-zinc-600" to-be-copied="#52525b">#52525b</ColorSquare>
            <ColorSquare class="bg-zinc-700" to-be-copied="#3f3f46">#3f3f46</ColorSquare>
            <ColorSquare class="bg-zinc-800" to-be-copied="#27272a">#27272a</ColorSquare>
            <ColorSquare class="bg-zinc-900" to-be-copied="#18181b">#18181b</ColorSquare>
            <ColorSquare class="bg-zinc-950" to-be-copied="#09090b">#09090b</ColorSquare>
        </ShadeGrid>

        <!-- Neutral -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Neutral</span>
            <ColorSquare class="bg-neutral-50" to-be-copied="#fafafa">#fafafa</ColorSquare>
            <ColorSquare class="bg-neutral-100" to-be-copied="#f5f5f5">#f5f5f5</ColorSquare>
            <ColorSquare class="bg-neutral-200" to-be-copied="#e5e5e5">#e5e5e5</ColorSquare>
            <ColorSquare class="bg-neutral-300" to-be-copied="#d4d4d4">#d4d4d4</ColorSquare>
            <ColorSquare class="bg-neutral-400" to-be-copied="#a3a3a3">#a3a3a3</ColorSquare>
            <ColorSquare class="bg-neutral-500" to-be-copied="#737373">#737373</ColorSquare>
            <ColorSquare class="bg-neutral-600" to-be-copied="#525252">#525252</ColorSquare>
            <ColorSquare class="bg-neutral-700" to-be-copied="#404040">#404040</ColorSquare>
            <ColorSquare class="bg-neutral-800" to-be-copied="#262626">#262626</ColorSquare>
            <ColorSquare class="bg-neutral-900" to-be-copied="#171717">#171717</ColorSquare>
            <ColorSquare class="bg-neutral-950" to-be-copied="#0a0a0a">#0a0a0a</ColorSquare>
        </ShadeGrid>

        <!-- Stone -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Stone</span>
            <ColorSquare class="bg-stone-50" to-be-copied="#fafaf9">#fafaf9</ColorSquare>
            <ColorSquare class="bg-stone-100" to-be-copied="#f5f5f4">#f5f5f4</ColorSquare>
            <ColorSquare class="bg-stone-200" to-be-copied="#e7e5e4">#e7e5e4</ColorSquare>
            <ColorSquare class="bg-stone-300" to-be-copied="#d6d3d1">#d6d3d1</ColorSquare>
            <ColorSquare class="bg-stone-400" to-be-copied="#a8a29e">#a8a29e</ColorSquare>
            <ColorSquare class="bg-stone-500" to-be-copied="#78716c">#78716c</ColorSquare>
            <ColorSquare class="bg-stone-600" to-be-copied="#57534e">#57534e</ColorSquare>
            <ColorSquare class="bg-stone-700" to-be-copied="#44403c">#44403c</ColorSquare>
            <ColorSquare class="bg-stone-800" to-be-copied="#292524">#292524</ColorSquare>
            <ColorSquare class="bg-stone-900" to-be-copied="#1c1917">#1c1917</ColorSquare>
            <ColorSquare class="bg-stone-950" to-be-copied="#0c0a09">#0c0a09</ColorSquare>
        </ShadeGrid>

        <!-- Red -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Red</span>
            <ColorSquare class="bg-red-50" to-be-copied="#fef2f2">#fef2f2</ColorSquare>
            <ColorSquare class="bg-red-100" to-be-copied="#fee2e2">#fee2e2</ColorSquare>
            <ColorSquare class="bg-red-200" to-be-copied="#fecaca">#fecaca</ColorSquare>
            <ColorSquare class="bg-red-300" to-be-copied="#fca5a5">#fca5a5</ColorSquare>
            <ColorSquare class="bg-red-400" to-be-copied="#f87171">#f87171</ColorSquare>
            <ColorSquare class="bg-red-500" to-be-copied="#ef4444">#ef4444</ColorSquare>
            <ColorSquare class="bg-red-600" to-be-copied="#dc2626">#dc2626</ColorSquare>
            <ColorSquare class="bg-red-700" to-be-copied="#b91c1c">#b91c1c</ColorSquare>
            <ColorSquare class="bg-red-800" to-be-copied="#991b1b">#991b1b</ColorSquare>
            <ColorSquare class="bg-red-900" to-be-copied="#7f1d1d">#7f1d1d</ColorSquare>
            <ColorSquare class="bg-red-950" to-be-copied="#450a0a">#450a0a</ColorSquare>
        </ShadeGrid>

        <!-- Orange -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Orange</span>
            <ColorSquare class="bg-orange-50" to-be-copied="#fff7ed">#fff7ed</ColorSquare>
            <ColorSquare class="bg-orange-100" to-be-copied="#ffedd5">#ffedd5</ColorSquare>
            <ColorSquare class="bg-orange-200" to-be-copied="#fed7aa">#fed7aa</ColorSquare>
            <ColorSquare class="bg-orange-300" to-be-copied="#fdba74">#fdba74</ColorSquare>
            <ColorSquare class="bg-orange-400" to-be-copied="#fb923c">#fb923c</ColorSquare>
            <ColorSquare class="bg-orange-500" to-be-copied="#f97316">#f97316</ColorSquare>
            <ColorSquare class="bg-orange-600" to-be-copied="#ea580c">#ea580c</ColorSquare>
            <ColorSquare class="bg-orange-700" to-be-copied="#c2410c">#c2410c</ColorSquare>
            <ColorSquare class="bg-orange-800" to-be-copied="#9a3412">#9a3412</ColorSquare>
            <ColorSquare class="bg-orange-900" to-be-copied="#7c2d12">#7c2d12</ColorSquare>
            <ColorSquare class="bg-orange-950" to-be-copied="#431407">#431407</ColorSquare>
        </ShadeGrid>

        <!-- Amber -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Amber</span>
            <ColorSquare class="bg-amber-50" to-be-copied="#fffbeb">#fffbeb</ColorSquare>
            <ColorSquare class="bg-amber-100" to-be-copied="#fef3c7">#fef3c7</ColorSquare>
            <ColorSquare class="bg-amber-200" to-be-copied="#fde68a">#fde68a</ColorSquare>
            <ColorSquare class="bg-amber-300" to-be-copied="#fcd34d">#fcd34d</ColorSquare>
            <ColorSquare class="bg-amber-400" to-be-copied="#fbbf24">#fbbf24</ColorSquare>
            <ColorSquare class="bg-amber-500" to-be-copied="#f59e0b">#f59e0b</ColorSquare>
            <ColorSquare class="bg-amber-600" to-be-copied="#d97706">#d97706</ColorSquare>
            <ColorSquare class="bg-amber-700" to-be-copied="#b45309">#b45309</ColorSquare>
            <ColorSquare class="bg-amber-800" to-be-copied="#92400e">#92400e</ColorSquare>
            <ColorSquare class="bg-amber-900" to-be-copied="#78350f">#78350f</ColorSquare>
            <ColorSquare class="bg-amber-950" to-be-copied="#451a03">#451a03</ColorSquare>
        </ShadeGrid>

        <!-- Yellow -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Yellow</span>
            <ColorSquare class="bg-yellow-50" to-be-copied="#fefce8">#fefce8</ColorSquare>
            <ColorSquare class="bg-yellow-100" to-be-copied="#fef9c3">#fef9c3</ColorSquare>
            <ColorSquare class="bg-yellow-200" to-be-copied="#fef08a">#fef08a</ColorSquare>
            <ColorSquare class="bg-yellow-300" to-be-copied="#fde047">#fde047</ColorSquare>
            <ColorSquare class="bg-yellow-400" to-be-copied="#facc15">#facc15</ColorSquare>
            <ColorSquare class="bg-yellow-500" to-be-copied="#eab308">#eab308</ColorSquare>
            <ColorSquare class="bg-yellow-600" to-be-copied="#ca8a04">#ca8a04</ColorSquare>
            <ColorSquare class="bg-yellow-700" to-be-copied="#a16207">#a16207</ColorSquare>
            <ColorSquare class="bg-yellow-800" to-be-copied="#854d0e">#854d0e</ColorSquare>
            <ColorSquare class="bg-yellow-900" to-be-copied="#713f12">#713f12</ColorSquare>
            <ColorSquare class="bg-yellow-950" to-be-copied="#422006">#422006</ColorSquare>
        </ShadeGrid>

        <!-- Lime -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Lime</span>
            <ColorSquare class="bg-lime-50" to-be-copied="#f7fee7">#f7fee7</ColorSquare>
            <ColorSquare class="bg-lime-100" to-be-copied="#ecfccb">#ecfccb</ColorSquare>
            <ColorSquare class="bg-lime-200" to-be-copied="#d9f99d">#d9f99d</ColorSquare>
            <ColorSquare class="bg-lime-300" to-be-copied="#bef264">#bef264</ColorSquare>
            <ColorSquare class="bg-lime-400" to-be-copied="#a3e635">#a3e635</ColorSquare>
            <ColorSquare class="bg-lime-500" to-be-copied="#84cc16">#84cc16</ColorSquare>
            <ColorSquare class="bg-lime-600" to-be-copied="#65a30d">#65a30d</ColorSquare>
            <ColorSquare class="bg-lime-700" to-be-copied="#4d7c0f">#4d7c0f</ColorSquare>
            <ColorSquare class="bg-lime-800" to-be-copied="#3f6212">#3f6212</ColorSquare>
            <ColorSquare class="bg-lime-900" to-be-copied="#365314">#365314</ColorSquare>
            <ColorSquare class="bg-lime-950" to-be-copied="#1a2e05">#1a2e05</ColorSquare>
        </ShadeGrid>

        <!-- Green -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Green</span>
            <ColorSquare class="bg-green-50" to-be-copied="#f0fdf4">#f0fdf4</ColorSquare>
            <ColorSquare class="bg-green-100" to-be-copied="#dcfce7">#dcfce7</ColorSquare>
            <ColorSquare class="bg-green-200" to-be-copied="#bbf7d0">#bbf7d0</ColorSquare>
            <ColorSquare class="bg-green-300" to-be-copied="#86efac">#86efac</ColorSquare>
            <ColorSquare class="bg-green-400" to-be-copied="#4ade80">#4ade80</ColorSquare>
            <ColorSquare class="bg-green-500" to-be-copied="#22c55e">#22c55e</ColorSquare>
            <ColorSquare class="bg-green-600" to-be-copied="#16a34a">#16a34a</ColorSquare>
            <ColorSquare class="bg-green-700" to-be-copied="#15803d">#15803d</ColorSquare>
            <ColorSquare class="bg-green-800" to-be-copied="#166534">#166534</ColorSquare>
            <ColorSquare class="bg-green-900" to-be-copied="#14532d">#14532d</ColorSquare>
            <ColorSquare class="bg-green-950" to-be-copied="#052e16">#052e16</ColorSquare>
        </ShadeGrid>

        <!-- Emerald -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Emerald</span>
            <ColorSquare class="bg-emerald-50" to-be-copied="#ecfdf5">#ecfdf5</ColorSquare>
            <ColorSquare class="bg-emerald-100" to-be-copied="#d1fae5">#d1fae5</ColorSquare>
            <ColorSquare class="bg-emerald-200" to-be-copied="#a7f3d0">#a7f3d0</ColorSquare>
            <ColorSquare class="bg-emerald-300" to-be-copied="#6ee7b7">#6ee7b7</ColorSquare>
            <ColorSquare class="bg-emerald-400" to-be-copied="#34d399">#34d399</ColorSquare>
            <ColorSquare class="bg-emerald-500" to-be-copied="#10b981">#10b981</ColorSquare>
            <ColorSquare class="bg-emerald-600" to-be-copied="#059669">#059669</ColorSquare>
            <ColorSquare class="bg-emerald-700" to-be-copied="#047857">#047857</ColorSquare>
            <ColorSquare class="bg-emerald-800" to-be-copied="#065f46">#065f46</ColorSquare>
            <ColorSquare class="bg-emerald-900" to-be-copied="#064e3b">#064e3b</ColorSquare>
            <ColorSquare class="bg-emerald-950" to-be-copied="#022c22">#022c22</ColorSquare>
        </ShadeGrid>

        <!-- Teal -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Teal</span>
            <ColorSquare class="bg-teal-50" to-be-copied="#f0fdfa">#f0fdfa</ColorSquare>
            <ColorSquare class="bg-teal-100" to-be-copied="#ccfbf1">#ccfbf1</ColorSquare>
            <ColorSquare class="bg-teal-200" to-be-copied="#99f6e4">#99f6e4</ColorSquare>
            <ColorSquare class="bg-teal-300" to-be-copied="#5eead4">#5eead4</ColorSquare>
            <ColorSquare class="bg-teal-400" to-be-copied="#2dd4bf">#2dd4bf</ColorSquare>
            <ColorSquare class="bg-teal-500" to-be-copied="#14b8a6">#14b8a6</ColorSquare>
            <ColorSquare class="bg-teal-600" to-be-copied="#0d9488">#0d9488</ColorSquare>
            <ColorSquare class="bg-teal-700" to-be-copied="#0f766e">#0f766e</ColorSquare>
            <ColorSquare class="bg-teal-800" to-be-copied="#115e59">#115e59</ColorSquare>
            <ColorSquare class="bg-teal-900" to-be-copied="#134e4a">#134e4a</ColorSquare>
            <ColorSquare class="bg-teal-950" to-be-copied="#042f2e">#042f2e</ColorSquare>
        </ShadeGrid>

        <!-- Cyan -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Cyan</span>
            <ColorSquare class="bg-cyan-50" to-be-copied="#ecfeff">#ecfeff</ColorSquare>
            <ColorSquare class="bg-cyan-100" to-be-copied="#cffafe">#cffafe</ColorSquare>
            <ColorSquare class="bg-cyan-200" to-be-copied="#a5f3fc">#a5f3fc</ColorSquare>
            <ColorSquare class="bg-cyan-300" to-be-copied="#67e8f9">#67e8f9</ColorSquare>
            <ColorSquare class="bg-cyan-400" to-be-copied="#22d3ee">#22d3ee</ColorSquare>
            <ColorSquare class="bg-cyan-500" to-be-copied="#06b6d4">#06b6d4</ColorSquare>
            <ColorSquare class="bg-cyan-600" to-be-copied="#0891b2">#0891b2</ColorSquare>
            <ColorSquare class="bg-cyan-700" to-be-copied="#0e7490">#0e7490</ColorSquare>
            <ColorSquare class="bg-cyan-800" to-be-copied="#155e75">#155e75</ColorSquare>
            <ColorSquare class="bg-cyan-900" to-be-copied="#164e63">#164e63</ColorSquare>
            <ColorSquare class="bg-cyan-950" to-be-copied="#083344">#083344</ColorSquare>
        </ShadeGrid>

        <!-- Sky -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Sky</span>
            <ColorSquare class="bg-sky-50" to-be-copied="#f0f9ff">#f0f9ff</ColorSquare>
            <ColorSquare class="bg-sky-100" to-be-copied="#e0f2fe">#e0f2fe</ColorSquare>
            <ColorSquare class="bg-sky-200" to-be-copied="#bae6fd">#bae6fd</ColorSquare>
            <ColorSquare class="bg-sky-300" to-be-copied="#7dd3fc">#7dd3fc</ColorSquare>
            <ColorSquare class="bg-sky-400" to-be-copied="#38bdf8">#38bdf8</ColorSquare>
            <ColorSquare class="bg-sky-500" to-be-copied="#0ea5e9">#0ea5e9</ColorSquare>
            <ColorSquare class="bg-sky-600" to-be-copied="#0284c7">#0284c7</ColorSquare>
            <ColorSquare class="bg-sky-700" to-be-copied="#0369a1">#0369a1</ColorSquare>
            <ColorSquare class="bg-sky-800" to-be-copied="#075985">#075985</ColorSquare>
            <ColorSquare class="bg-sky-900" to-be-copied="#0c4a6e">#0c4a6e</ColorSquare>
            <ColorSquare class="bg-sky-950" to-be-copied="#082f49">#082f49</ColorSquare>
        </ShadeGrid>

        <!-- Blue -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Blue</span>
            <ColorSquare class="bg-blue-50" to-be-copied="#eff6ff">#eff6ff</ColorSquare>
            <ColorSquare class="bg-blue-100" to-be-copied="#dbeafe">#dbeafe</ColorSquare>
            <ColorSquare class="bg-blue-200" to-be-copied="#bfdbfe">#bfdbfe</ColorSquare>
            <ColorSquare class="bg-blue-300" to-be-copied="#93c5fd">#93c5fd</ColorSquare>
            <ColorSquare class="bg-blue-400" to-be-copied="#60a5fa">#60a5fa</ColorSquare>
            <ColorSquare class="bg-blue-500" to-be-copied="#3b82f6">#3b82f6</ColorSquare>
            <ColorSquare class="bg-blue-600" to-be-copied="#2563eb">#2563eb</ColorSquare>
            <ColorSquare class="bg-blue-700" to-be-copied="#1d4ed8">#1d4ed8</ColorSquare>
            <ColorSquare class="bg-blue-800" to-be-copied="#1e40af">#1e40af</ColorSquare>
            <ColorSquare class="bg-blue-900" to-be-copied="#1e3a8a">#1e3a8a</ColorSquare>
            <ColorSquare class="bg-blue-950" to-be-copied="#172554">#172554</ColorSquare>
        </ShadeGrid>

        <!-- Indigo -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Indigo</span>
            <ColorSquare class="bg-indigo-50" to-be-copied="#eef2ff">#eef2ff</ColorSquare>
            <ColorSquare class="bg-indigo-100" to-be-copied="#e0e7ff">#e0e7ff</ColorSquare>
            <ColorSquare class="bg-indigo-200" to-be-copied="#c7d2fe">#c7d2fe</ColorSquare>
            <ColorSquare class="bg-indigo-300" to-be-copied="#a5b4fc">#a5b4fc</ColorSquare>
            <ColorSquare class="bg-indigo-400" to-be-copied="#818cf8">#818cf8</ColorSquare>
            <ColorSquare class="bg-indigo-500" to-be-copied="#6366f1">#6366f1</ColorSquare>
            <ColorSquare class="bg-indigo-600" to-be-copied="#4f46e5">#4f46e5</ColorSquare>
            <ColorSquare class="bg-indigo-700" to-be-copied="#4338ca">#4338ca</ColorSquare>
            <ColorSquare class="bg-indigo-800" to-be-copied="#3730a3">#3730a3</ColorSquare>
            <ColorSquare class="bg-indigo-900" to-be-copied="#312e81">#312e81</ColorSquare>
            <ColorSquare class="bg-indigo-950" to-be-copied="#1e1b4b">#1e1b4b</ColorSquare>
        </ShadeGrid>

        <!-- Violet -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Violet</span>
            <ColorSquare class="bg-violet-50" to-be-copied="#f5f3ff">#f5f3ff</ColorSquare>
            <ColorSquare class="bg-violet-100" to-be-copied="#ede9fe">#ede9fe</ColorSquare>
            <ColorSquare class="bg-violet-200" to-be-copied="#ddd6fe">#ddd6fe</ColorSquare>
            <ColorSquare class="bg-violet-300" to-be-copied="#c4b5fd">#c4b5fd</ColorSquare>
            <ColorSquare class="bg-violet-400" to-be-copied="#a78bfa">#a78bfa</ColorSquare>
            <ColorSquare class="bg-violet-500" to-be-copied="#8b5cf6">#8b5cf6</ColorSquare>
            <ColorSquare class="bg-violet-600" to-be-copied="#7c3aed">#7c3aed</ColorSquare>
            <ColorSquare class="bg-violet-700" to-be-copied="#6d28d9">#6d28d9</ColorSquare>
            <ColorSquare class="bg-violet-800" to-be-copied="#5b21b6">#5b21b6</ColorSquare>
            <ColorSquare class="bg-violet-900" to-be-copied="#4c1d95">#4c1d95</ColorSquare>
            <ColorSquare class="bg-violet-950" to-be-copied="#2e1065">#2e1065</ColorSquare>
        </ShadeGrid>

        <!-- Purple -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Purple</span>
            <ColorSquare class="bg-purple-50" to-be-copied="#faf5ff">#faf5ff</ColorSquare>
            <ColorSquare class="bg-purple-100" to-be-copied="#f3e8ff">#f3e8ff</ColorSquare>
            <ColorSquare class="bg-purple-200" to-be-copied="#e9d5ff">#e9d5ff</ColorSquare>
            <ColorSquare class="bg-purple-300" to-be-copied="#d8b4fe">#d8b4fe</ColorSquare>
            <ColorSquare class="bg-purple-400" to-be-copied="#c084fc">#c084fc</ColorSquare>
            <ColorSquare class="bg-purple-500" to-be-copied="#a855f7">#a855f7</ColorSquare>
            <ColorSquare class="bg-purple-600" to-be-copied="#9333ea">#9333ea</ColorSquare>
            <ColorSquare class="bg-purple-700" to-be-copied="#7e22ce">#7e22ce</ColorSquare>
            <ColorSquare class="bg-purple-800" to-be-copied="#6b21a8">#6b21a8</ColorSquare>
            <ColorSquare class="bg-purple-900" to-be-copied="#581c87">#581c87</ColorSquare>
            <ColorSquare class="bg-purple-950" to-be-copied="#3b0764">#3b0764</ColorSquare>
        </ShadeGrid>

        <!-- Fuchsia -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Fuchsia</span>
            <ColorSquare class="bg-fuchsia-50" to-be-copied="#fdf4ff">#fdf4ff</ColorSquare>
            <ColorSquare class="bg-fuchsia-100" to-be-copied="#fae8ff">#fae8ff</ColorSquare>
            <ColorSquare class="bg-fuchsia-200" to-be-copied="#f5d0fe">#f5d0fe</ColorSquare>
            <ColorSquare class="bg-fuchsia-300" to-be-copied="#f0abfc">#f0abfc</ColorSquare>
            <ColorSquare class="bg-fuchsia-400" to-be-copied="#e879f9">#e879f9</ColorSquare>
            <ColorSquare class="bg-fuchsia-500" to-be-copied="#d946ef">#d946ef</ColorSquare>
            <ColorSquare class="bg-fuchsia-600" to-be-copied="#c026d3">#c026d3</ColorSquare>
            <ColorSquare class="bg-fuchsia-700" to-be-copied="#a21caf">#a21caf</ColorSquare>
            <ColorSquare class="bg-fuchsia-800" to-be-copied="#86198f">#86198f</ColorSquare>
            <ColorSquare class="bg-fuchsia-900" to-be-copied="#701a75">#701a75</ColorSquare>
            <ColorSquare class="bg-fuchsia-950" to-be-copied="#4a044e">#4a044e</ColorSquare>
        </ShadeGrid>

        <!-- Pink -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Pink</span>
            <ColorSquare class="bg-pink-50" to-be-copied="#fdf2f8">#fdf2f8</ColorSquare>
            <ColorSquare class="bg-pink-100" to-be-copied="#fce7f3">#fce7f3</ColorSquare>
            <ColorSquare class="bg-pink-200" to-be-copied="#fbcfe8">#fbcfe8</ColorSquare>
            <ColorSquare class="bg-pink-300" to-be-copied="#f9a8d4">#f9a8d4</ColorSquare>
            <ColorSquare class="bg-pink-400" to-be-copied="#f472b6">#f472b6</ColorSquare>
            <ColorSquare class="bg-pink-500" to-be-copied="#ec4899">#ec4899</ColorSquare>
            <ColorSquare class="bg-pink-600" to-be-copied="#db2777">#db2777</ColorSquare>
            <ColorSquare class="bg-pink-700" to-be-copied="#be185d">#be185d</ColorSquare>
            <ColorSquare class="bg-pink-800" to-be-copied="#9d174d">#9d174d</ColorSquare>
            <ColorSquare class="bg-pink-900" to-be-copied="#831843">#831843</ColorSquare>
            <ColorSquare class="bg-pink-950" to-be-copied="#500724">#500724</ColorSquare>
        </ShadeGrid>

        <!-- Rose -->
        <ShadeGrid>
            <span class="flex items-center justify-center">Rose</span>
            <ColorSquare class="bg-rose-50" to-be-copied="#fff1f2">#fff1f2</ColorSquare>
            <ColorSquare class="bg-rose-100" to-be-copied="#ffe4e6">#ffe4e6</ColorSquare>
            <ColorSquare class="bg-rose-200" to-be-copied="#fecdd3">#fecdd3</ColorSquare>
            <ColorSquare class="bg-rose-300" to-be-copied="#fda4af">#fda4af</ColorSquare>
            <ColorSquare class="bg-rose-400" to-be-copied="#fb7185">#fb7185</ColorSquare>
            <ColorSquare class="bg-rose-500" to-be-copied="#f43f5e">#f43f5e</ColorSquare>
            <ColorSquare class="bg-rose-600" to-be-copied="#e11d48">#e11d48</ColorSquare>
            <ColorSquare class="bg-rose-700" to-be-copied="#be123c">#be123c</ColorSquare>
            <ColorSquare class="bg-rose-800" to-be-copied="#9f1239">#9f1239</ColorSquare>
            <ColorSquare class="bg-rose-900" to-be-copied="#881337">#881337</ColorSquare>
            <ColorSquare class="bg-rose-950" to-be-copied="#4c0519">#4c0519</ColorSquare>
        </ShadeGrid>
    </main>
</template>

<script setup>
import { useBreakpoints, breakpointsTailwind } from "@vueuse/core";
import { Icon } from "@iconify/vue";

import ShadeGrid from "./components/ShadeGrid.vue";
import ColorSquare from "./components/ColorSquare.vue";

const breakpoints = useBreakpoints(breakpointsTailwind);
const onMobile = breakpoints.smaller("xl");
</script>
