```
<!-- Header / Branding -->
<header class="bg-slate-900 border-b border-slate-800 sticky top-0 z-30 shadow-xl">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex flex-col md:flex-row justify-between items-center gap-4">
        <div class="flex items-center space-x-3">
            <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-red-600 to-cyan-500 flex items-center justify-center font-black text-white text-lg shadow-lg">B</div>
            <div>
                <h1 class="text-xl font-bold tracking-tight text-white">Binary Trading Cards LLC</h1>
                <p class="text-xs text-slate-400">www.binarytradingcards.com • Wholesale Order Portal</p>
            </div>
        </div>
        <!-- Tier Schedule Badge Banner -->
        <div class="flex flex-wrap items-center gap-2 text-xs font-medium bg-slate-950/80 px-4 py-2 rounded-xl border border-slate-800">
            <span class="text-slate-400 font-semibold mr-1">Tiers:</span>
            <span class="px-2 py-1 rounded bg-slate-800 text-slate-300">1-24: $12</span>
            <span class="px-2 py-1 rounded bg-slate-800 text-slate-300">25-49: $10</span>
            <span class="px-2 py-1 rounded bg-slate-800 text-slate-300">50-99: $9</span>
            <span class="px-2 py-1 rounded bg-slate-800 text-slate-300">100-149: $8</span>
            <span class="px-2 py-1 rounded bg-red-950/80 text-red-300 border border-red-900/50 font-bold">150+: $7 🔥</span>
        </div>
    </div>
</header>

<!-- Main Container -->
<main class="flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-8 grid grid-cols-1 lg:grid-cols-3 gap-8">

    <!-- Left 2 Cols: Product Catalog & Shop Info -->
    <div class="lg:col-span-2 space-y-8">

        <!-- Shop Info Section -->
        <section class="bg-slate-900 border border-slate-800 rounded-2xl p-6 shadow-md">
            <h2 class="text-base font-bold text-white uppercase tracking-wider mb-4 flex items-center gap-2">
                <svg class="w-5 h-5 text-red-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/></svg>
                1. Retail Partner Details
            </h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 text-sm">
                <div>
                    <label class="block text-slate-400 mb-1 font-medium">Store Name *</label>
                    <input type="text" id="storeName" placeholder="e.g. Metro City Collectibles" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-white placeholder-slate-600 focus:outline-none focus:border-red-500 transition">
                </div>
                <div>
                    <label class="block text-slate-400 mb-1 font-medium">Contact Person *</label>
                    <input type="text" id="contactName" placeholder="e.g. John Doe" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-white placeholder-slate-600 focus:outline-none focus:border-red-500 transition">
                </div>
                <div>
                    <label class="block text-slate-400 mb-1 font-medium">Email Address *</label>
                    <input type="email" id="email" placeholder="store@example.com" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-white placeholder-slate-600 focus:outline-none focus:border-red-500 transition">
                </div>
                <div>
                    <label class="block text-slate-400 mb-1 font-medium">Phone Number *</label>
                    <input type="tel" id="phone" placeholder="(555) 000-0000" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-white placeholder-slate-600 focus:outline-none focus:border-red-500 transition">
                </div>
                <div class="sm:col-span-2">
                    <label class="block text-slate-400 mb-1 font-medium">Shipping Address *</label>
                    <input type="text" id="address" placeholder="Street Address, City, State, ZIP" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-white placeholder-slate-600 focus:outline-none focus:border-red-500 transition">
                </div>
                <div>
                    <label class="block text-slate-400 mb-1 font-medium">Instagram Handle (Optional)</label>
                    <input type="text" id="instagram" placeholder="@shophandle" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-white placeholder-slate-600 focus:outline-none focus:border-red-500 transition">
                </div>
                <div>
                    <label class="block text-slate-400 mb-1 font-medium">Facebook Page (Optional)</label>
                    <input type="text" id="facebook" placeholder="facebook.com/shop" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-white placeholder-slate-600 focus:outline-none focus:border-red-500 transition">
                </div>
            </div>
        </section>

        <!-- Product Selection Section -->
        <section class="bg-slate-900 border border-slate-800 rounded-2xl p-6 shadow-md">
            <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 mb-6">
                <div>
                    <h2 class="text-base font-bold text-white uppercase tracking-wider flex items-center gap-2">
                        <svg class="w-5 h-5 text-cyan-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4"/></svg>
                        2. Select Graded Card Guard Colors
                    </h2>
                    <p class="text-xs text-slate-400 mt-1">Select quantities across 46 colors. Pricing applies to total units ordered.</p>
                </div>
                <button type="button" onclick="resetAllQuantities()" class="text-xs text-red-400 hover:text-red-300 font-medium px-3 py-1.5 rounded-lg bg-red-950/40 border border-red-900/50 transition">Reset Quantities</button>
            </div>

            <!-- Product Grid -->
            <div id="productGrid" class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
                <!-- Injected via JavaScript -->
            </div>
        </section>

    </div>

    <!-- Right Col: Sticky Summary & Checkout -->
    <div class="lg:col-span-1">
        <div class="sticky top-24 bg-slate-900 border border-slate-800 rounded-2xl p-6 shadow-2xl space-y-6">
            <h2 class="text-base font-bold text-white uppercase tracking-wider border-b border-slate-800 pb-3 flex items-center justify-between">
                <span>Order Summary</span>
                <span id="badgeTier" class="text-xs px-2.5 py-1 rounded-full bg-slate-800 text-slate-300 font-semibold">Tier: $12/unit</span>
            </h2>

            <!-- Progress to Next Tier -->
            <div class="space-y-2 bg-slate-950 p-4 rounded-xl border border-slate-800/80">
                <div class="flex justify-between text-xs font-semibold">
                    <span id="tierStatusText" class="text-slate-300">Calculating...</span>
                    <span id="tierNextGoal" class="text-red-400"></span>
                </div>
                <div class="w-full bg-slate-800 h-2 rounded-full overflow-hidden">
                    <div id="tierProgressBar" class="bg-gradient-to-r from-red-600 to-cyan-400 h-full w-0 transition-all duration-300"></div>
                </div>
            </div>

            <!-- Calculation breakdown -->
            <div class="space-y-3 text-sm">
                <div class="flex justify-between text-slate-400">
                    <span>Total Units Selected:</span>
                    <span id="summaryTotalUnits" class="font-bold text-white">0 units</span>
                </div>
                <div class="flex justify-between text-slate-400">
                    <span>Current Unit Price:</span>
                    <span id="summaryUnitPrice" class="font-bold text-white">$12.00 / unit</span>
                </div>
                <div class="flex justify-between text-slate-400">
                    <span>Subtotal:</span>
                    <span id="summarySubtotal" class="font-bold text-white">$0.00</span>
                </div>
                <div class="flex justify-between text-slate-400">
                    <span>Estimated Shipping:</span>
                    <span id="summaryShipping" class="font-bold text-white">$15.00</span>
                </div>
                <div class="text-xs text-slate-500 italic text-right" id="shippingNotice">Free shipping on orders over $300!</div>
            </div>

            <!-- Grand Total -->
            <div class="pt-4 border-t border-slate-800 flex justify-between items-baseline">
                <span class="text-base font-bold text-white">Grand Total:</span>
                <span id="summaryGrandTotal" class="text-2xl font-black text-red-500">$0.00</span>
            </div>

            <!-- Submit Button -->
            <button type="button" onclick="submitOrder()" class="w-full py-3.5 px-4 bg-gradient-to-r from-red-600 to-red-700 hover:from-red-500 hover:to-red-600 text-white font-bold rounded-xl shadow-lg shadow-red-950/50 transition transform active:scale-95 flex items-center justify-center gap-2">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012-2m-6 9l2 2 4-4"/></svg>
                Review &amp; Submit Order
            </button>
        </div>
    </div>

</main>

<!-- Modal / Invoice Preview Overlay -->
<div id="invoiceModal" class="fixed inset-0 z-50 bg-slate-950/80 backdrop-blur-sm hidden flex items-center justify-center p-4 overflow-y-auto">
    <div class="bg-slate-900 border border-slate-800 rounded-2xl max-w-2xl w-full p-6 sm:p-8 shadow-2xl space-y-6 my-8">
        <div class="flex justify-between items-start border-b border-slate-800 pb-4">
            <div>
                <h3 class="text-xl font-bold text-white">Wholesale Order Summary</h3>
                <p class="text-xs text-slate-400">Binary Trading Cards LLC • www.binarytradingcards.com</p>
            </div>
            <button type="button" onclick="closeModal()" class="text-slate-400 hover:text-white p-1 rounded-lg bg-slate-800/50">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>
        </div>

        <!-- Modal Content (Filled via JS) -->
        <div id="modalBody" class="space-y-4 text-sm text-slate-300 max-h-96 overflow-y-auto pr-2">
            <!-- Details injected -->
        </div>

        <div class="border-t border-slate-800 pt-4 flex gap-4">
            <button type="button" onclick="closeModal()" class="flex-1 py-3 bg-slate-800 hover:bg-slate-700 font-semibold rounded-xl text-white transition">Back to Edit</button>
            <button type="button" onclick="confirmOrderSubmission()" class="flex-1 py-3 bg-red-600 hover:bg-red-500 font-bold rounded-xl text-white shadow-lg transition">Confirm &amp; Send Order</button>
        </div>
    </div>
</div>

<!-- Footer -->
<footer class="bg-slate-900 border-t border-slate-800 mt-auto py-6 text-center text-xs text-slate-500">
    <p>Binary Trading Cards LLC • Wholesale &amp; Consignment Division • Contact: support@binarytradingcards.com</p>
</footer>

<!-- JavaScript Application Logic -->
<script>
    // 46 Graded Card Guard Colors
    const colors = [
        "YELLOW", "PURPLE", "RED", "PINK", "BLUE", "GOLDEN", "CRYSTAL", "ORANGE", "CORAL", "SOLAR DUST",
        "MIDNIGHT BLUE", "CRIMSON BLACK", "OCEAN", "LUNAR", "BIOHAZARD", "THUNDERSTORM", "COSMO", "ICEBERG", "SUNSET", "SOLAR SKY",
        "CYBER CYAN", "PASTEL SKY", "ICE AGE", "ARTIC NIGHT", "PINK CARBON", "PURPLE ACID", "VIOLA GLASS", "MAGENTA", "STORM", "SUNFLARE",
        "CRYSTAL JADE", "ROSSO CORSA", "PURPLE ICE", "LEMON LIME", "TOXIC VOID", "DARK MATTER", "COCKTAIL", "CRYSTAL BLUE", "AQUA VIOLET", "TROPICAL NEON",
        "KALEIDOSCOPE", "SUNRISE", "EMBER", "BURNT ORANGE", "ELEMENTAL"
    ];

    // State object for quantities
    let quantities = {};
    colors.forEach(c => quantities[c] = 0);

    // Initialize Product Grid
    function renderProductGrid() {
        const grid = document.getElementById('productGrid');
        grid.innerHTML = '';

        colors.forEach((color, index) => {
            const qty = quantities[color];
            const card = document.createElement('div');
            card.className = `bg-slate-950 border ${qty > 0 ? 'border-red-500/80 shadow-lg shadow-red-950/30' : 'border-slate-800'} rounded-xl p-3 flex flex-col justify-between transition-all`;
            
            card.innerHTML = `
                <div class="flex items-center space-x-3 mb-3">
                    <div class="w-10 h-10 rounded-lg bg-slate-900 border border-slate-800 flex items-center justify-center font-bold text-xs text-slate-400 overflow-hidden relative">
                        <span class="absolute inset-0 opacity-20 bg-gradient-to-br from-red-500 to-cyan-500"></span>
                        <span>#${index + 1}</span>
                    </div>
                    <div class="flex-1 min-w-0">
                        <h4 class="text-xs font-semibold text-white truncate">${color}</h4>
                        <p class="text-[10px] text-slate-500">Card Guard</p>
                    </div>
                </div>
                <div class="flex items-center justify-between bg-slate-900/90 rounded-lg p-1 border border-slate-800">
                    <button type="button" onclick="updateQty('${color}', -1)" class="w-8 h-8 rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-300 font-bold flex items-center justify-center transition">-</button>
                    <input type="number" id="qty-${index}" min="0" value="${qty}" onchange="setQty('${color}', this.value)" class="w-12 bg-transparent text-center text-sm font-bold text-white focus:outline-none">
                    <button type="button" onclick="updateQty('${color}', 1)" class="w-8 h-8 rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-300 font-bold flex items-center justify-center transition">+</button>
                </div>
            `;
            grid.appendChild(card);
        });
        calculateTotals();
    }

    function updateQty(color, delta) {
        quantities[color] = Math.max(0, (quantities[color] || 0) + delta);
        renderProductGrid();
    }

    function setQty(color, val) {
        quantities[color] = Math.max(0, parseInt(val) || 0);
        renderProductGrid();
    }

    function resetAllQuantities() {
        colors.forEach(c => quantities[c] = 0);
        renderProductGrid();
    }

    // Tier pricing logic
    function getUnitPrice(totalUnits) {
        if (totalUnits >= 150) return 7.00;
        if (totalUnits >= 100) return 8.00;
        if (totalUnits >= 50) return 9.00;
        if (totalUnits >= 25) return 10.00;
        return 12.00;
    }

    function calculateTotals() {
        let totalUnits = 0;
        Object.values(quantities).forEach(q => totalUnits += q);

        const unitPrice = getUnitPrice(totalUnits);
        const subtotal = totalUnits * unitPrice;
        const shipping = (totalUnits === 0) ? 0 : (subtotal >= 300 ? 0 : 15.00);
        const grandTotal = subtotal + shipping;

        // Update UI Summary
        document.getElementById('summaryTotalUnits').innerText = `${totalUnits} units`;
        document.getElementById('summaryUnitPrice').innerText = `$${unitPrice.toFixed(2)} / unit`;
        document.getElementById('summarySubtotal').innerText = `$${subtotal.toFixed(2)}`;
        
        const shippingEl = document.getElementById('summaryShipping');
        const noticeEl = document.getElementById('shippingNotice');
        if (totalUnits === 0) {
            shippingEl.innerText = '$0.00';
            noticeEl.innerText = 'Free shipping on orders over $300!';
        } else if (shipping === 0) {
            shippingEl.innerText = 'FREE';
            noticeEl.innerText = '🎉 Free shipping threshold reached ($300+)';
        } else {
            shippingEl.innerText = '$15.00';
            const neededForFree = Math.max(0, 300 - subtotal);
            noticeEl.innerText = `Add $${neededForFree.toFixed(2)} more for FREE shipping!`;
        }

        document.getElementById('summaryGrandTotal').innerText = `$${grandTotal.toFixed(2)}`;

        // Badge & Progress bar for next tier
        updateTierProgress(totalUnits, unitPrice);
    }

    function updateTierProgress(totalUnits, currentPrice) {
        let nextGoal = 25;
        let currentTierName = "Tier 1 ($12)";
        let progressPct = 0;

        if (totalUnits >= 150) {
            currentTierName = "🔥 Best Value Tier ($7)";
            nextGoal = 150;
            progressPct = 100;
            document.getElementById('tierStatusText').innerText = currentTierName;
            document.getElementById('tierNextGoal').innerText = "Max Tier Unlocked!";
        } else {
            if (totalUnits < 25) {
                nextGoal = 25;
                currentTierName = "1–24 Units ($12)";
                progressPct = (totalUnits / 25) * 100;
            } else if (totalUnits < 50) {
                nextGoal = 50;
                currentTierName = "25–49 Units ($10)";
                progressPct = ((totalUnits - 25) / 25) * 100;
            } else if (totalUnits < 100) {
                nextGoal = 100;
                currentTierName = "50–99 Units ($9)";
                progressPct = ((totalUnits - 50) / 50) * 100;
            } else if (totalUnits < 150) {
                nextGoal = 150;
                currentTierName = "100–149 Units ($8)";
                progressPct = ((totalUnits - 100) / 50) * 100;
            }
            document.getElementById('tierStatusText').innerText = currentTierName;
            document.getElementById('tierNextGoal').innerText = `${nextGoal - totalUnits} units to next tier`;
        }

        document.getElementById('badgeTier').innerText = `$${currentPrice.toFixed(2)}/unit`;
        document.getElementById('tierProgressBar').style.width = `${Math.min(100, Math.max(0, progressPct))}%`;
    }

    function submitOrder() {
        const storeName = document.getElementById('storeName').value.trim();
        const contactName = document.getElementById('contactName').value.trim();
        const email = document.getElementById('email').value.trim();
        const phone = document.getElementById('phone').value.trim();
        const address = document.getElementById('address').value.trim();

        if (!storeName || !contactName || !email || !phone || !address) {
            alert('Please fill out all required Retail Partner Details before submitting.');
            return;
        }

        let totalUnits = 0;
        Object.values(quantities).forEach(q => totalUnits += q);
        if (totalUnits === 0) {
            alert('Please select at least one unit to order.');
            return;
        }

        const unitPrice = getUnitPrice(totalUnits);
        const subtotal = totalUnits * unitPrice;
        const shipping = subtotal >= 300 ? 0 : 15.00;
        const grandTotal = subtotal + shipping;

        let itemsHtml = '<ul class="divide-y divide-slate-800">';
        colors.forEach(color => {
            const q = quantities[color];
            if (q > 0) {
                itemsHtml += `<li class="py-2 flex justify-between text-xs"><span>${color} (x${q})</span> <span class="font-bold text-white">$${(q * unitPrice).toFixed(2)}</span></li>`;
            }
        });
        itemsHtml += '</ul>';

        const modalBody = document.getElementById('modalBody');
        modalBody.innerHTML = `
            <div class="bg-slate-950 p-4 rounded-xl border border-slate-800 space-y-2 text-xs">
                <p><strong>Store:</strong> ${storeName}</p>
                <p><strong>Contact:</strong> ${contactName} (${phone} / ${email})</p>
                <p><strong>Shipping Address:</strong> ${address}</p>
            </div>
            <div>
                <h4 class="text-xs font-bold uppercase tracking-wider text-slate-400 mb-2">Selected Items</h4>
                ${itemsHtml}
            </div>
            <div class="bg-slate-950 p-4 rounded-xl border border-slate-800 space-y-1 text-xs">
                <div class="flex justify-between"><span>Total Units:</span> <strong class="text-white">${totalUnits}</strong></div>
                <div class="flex justify-between"><span>Unit Price Tier:</span> <strong class="text-white">$${unitPrice.toFixed(2)} / unit</strong></div>
                <div class="flex justify-between"><span>Subtotal:</span> <strong class="text-white">$${subtotal.toFixed(2)}</strong></div>
                <div class="flex justify-between"><span>Shipping:</span> <strong class="text-white">${shipping === 0 ? 'FREE' : '$15.00'}</strong></div>
                <div class="flex justify-between border-t border-slate-800 pt-2 text-sm font-bold text-red-400"><span>Grand Total:</span> <span>$${grandTotal.toFixed(2)}</span></div>
            </div>
        `;

        document.getElementById('invoiceModal').classList.remove('hidden');
    }

    function closeModal() {
        document.getElementById('invoiceModal').classList.add('hidden');
    }

    function confirmOrderSubmission() {
        alert('Order successfully submitted to Binary Trading Cards LLC! We will contact you shortly with fulfillment details.');
        closeModal();
        resetAllQuantities();
        window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    // Initialize on load
    window.onload = function() {
        renderProductGrid();
    };
</script>

```