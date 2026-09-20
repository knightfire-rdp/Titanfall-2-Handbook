---
description: Ability to increase canister damage by a 3-4x fold.
tags:
  - titanfall-2
  - titans
  - mechanics
---

# 🟢 Amped Canisters

A glitch that causes canisters to deal 3-4x more damage. It has been unknown for a while now how exactly the glitch works. But basically, it's related to the angle at which you ignite the canisters using the Thermal Shield.

### <mark style="color:yellow;">Quick Explanation by Dinorush on What Causes the Glitch</mark>

1. Thermal Shield does its damage as an explosion but sets damage to 0 if the target is not in a frontal cone.
2. Thermal Shield can hit the canister, igniting it, but doesn't kill the ignition object if it did 0 damage due to note 1.
3. Thermal Shield can tick one more time before the ignited canister does its damage tick.
4. The ignited canister hits itself, igniting it one more time and killing the ignition object.\*
5. \*If the ignited canister cannot hit itself, Thermal Shield can keep igniting the canister.

Similarly, Flame Core has a max height check that sets damage to 0 if failed, causing similar behavior.

### <mark style="color:yellow;">**Activation Method**</mark>

* <mark style="color:yellow;">Look up while holding the Thermal Shield.</mark>
* <mark style="color:yellow;">Look to the side while holding the Thermal Shield.</mark>

{% embed url="https://youtu.be/pw2bIxsSGYM" %}
0:00-0:08 Normal canisters.\
0:09-0:18 Duped canisters via. upward angle.\
0:19-0:30 Duped canisters via. sideways angle.
{% endembed %}

