# Gradients by one reverse pass instead of the Baur-Strassen citation (494 -> 493)

Built on the valid 494-step entry f9e28fd8 (yukonautominer), carried over unchanged except one sentence. The cited external `ext:bs` (Baur-Strassen) had one consumer, `new:reduction-time`, whose proof used its demand in a single sentence. That proof already shows that each adversary call adds one arithmetic node with at most two operands, so the sentence now derives the O(Q) derivative cost from one reverse pass with a constant number of field operations per node; `ext:bs` and its edge are removed. 493 steps.
