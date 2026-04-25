# 1S 2-Inch High-KV Toothpick FPV Quad

A custom ultra-light **1S 2-inch toothpick FPV quad** designed around a specific idea:

> **Use a small, high-KV 2-inch powertrain for extreme responsiveness and punch, but place it on a larger 96 mm frame to gain stability, grip, protection, and a more locked-in flight feel.**

This is not a normal compact 2-inch toothpick, and it is not trying to become a slow, floaty 3-inch cruiser.

It is designed to sit between both concepts:

- **2-inch response**
- **high-KV punch**
- **low prop inertia**
- **larger-frame stability**
- **better component protection**
- **very low AUW**
- **extreme 1S thrust-to-weight**

In short:

> **A 1S 2-inch toothpick with 5-inch attitude.**

---

## Core Concept

Most 2-inch toothpick frames are around **85 mm motor-to-motor**. They are compact, light, and responsive, but can also feel twitchy and nervous at speed.

This frame uses a larger **96 mm wheelbase**, while still staying extremely light. The larger wheelbase gives the quad more mechanical leverage, more stability, better component protection, and a less twitchy feel.

At the same time, the quad still uses:

- high-KV 1002 motors
- 2-inch lightweight bi-blade props
- very low prop inertia
- low AUW
- 1S power

This keeps the quad extremely responsive and punchy.

The design goal is:

```text
2-inch responsiveness
+
high-KV punch
+
96 mm locked-in frame feel
=
responsive, stable, aggressive 1S micro quad
```

---

## Main Specs

| Item | Specification |
|---|---:|
| Class | 1S 2-inch toothpick |
| Frame wheelbase | 96 mm |
| Typical 2-inch frame reference | ~85 mm |
| Frame material | Carbon fiber |
| Frame thickness | 2 mm |
| Frame area | ~1258 mm² |
| Estimated frame weight | ~3.8–4.0 g |
| Motors | 1002 high-KV brushless |
| Planned KV | 25000KV |
| Alternative KV | 22000KV |
| Motor weight | ~2.5 g each including wires |
| Props | Gemfan GF2015 bi-blade |
| Prop size | 2.0 inch |
| Experimental prop size | 2.2 inch low pitch |
| Battery | 1S LiHV, LAVA 580 mAh |
| Estimated dry weight | ~25–26 g |
| Estimated AUW | ~39–40 g |
| Estimated thrust | ~400–412 g total |
| Estimated thrust-to-weight | ~10:1 |

---

## Estimated Weight Breakdown

| Component | Estimated Weight |
|---|---:|
| 2 mm carbon frame | ~3.8–4.0 g |
| 4x 1002 motors, including wires | ~10.0 g |
| Canopy | ~0.55 g |
| Camera | ~1.5 g |
| FC AIO | ~4.0 g |
| Battery connector + wires | ~2.0 g |
| 4x Gemfan GF2015 bi-blade props | ~2.0 g |
| 12x M1.4 motor screws | ~0.5–0.8 g |
| 4x FC rubber grommets | ~0.2–0.4 g |
| 4x M2 FC screws | ~0.4–0.8 g |
| 4x 3D printed motor dampers | ~0.1 g |
| 3D printed FC protector | ~0.2 g |

Estimated dry weight without battery:

```text
~25–26 g
```

With a LAVA 1S 580 mAh LiHV battery:

```text
~39–40 g AUW
```

---

## Frame Weight Estimate

The final frame area is approximately:

```text
1258 mm²
```

Frame thickness:

```text
2 mm
```

Volume:

```text
1258 mm² × 2 mm = 2516 mm³
```

Convert to cubic centimeters:

```text
2516 mm³ = 2.516 cm³
```

Using a typical carbon fiber composite density of roughly **1.5–1.6 g/cm³**:

```text
2.516 cm³ × 1.5 g/cm³ = 3.77 g
2.516 cm³ × 1.6 g/cm³ = 4.03 g
```

Estimated frame weight:

```text
~3.8–4.0 g
```

This is extremely light for a 96 mm frame that can support larger-than-normal 2-inch prop options.

---

## Why a 96 mm Frame?

Most normal 2-inch toothpick frames are around **85 mm**. This frame is larger at **96 mm**, which gives several advantages.

### 1. More Control Authority

A quad controls roll and pitch by creating thrust differences between motors. The motors act at a distance from the center of gravity.

The basic relationship is:

```text
torque = force × arm length
```

Or, for a quad:

```text
roll/pitch torque = thrust difference × motor distance from center
```

Compared to an 85 mm frame:

```text
96 / 85 = 1.129
```

This means the 96 mm frame gives about:

```text
~13% more motor leverage
```

So for the same thrust difference, the motors have more mechanical advantage for roll and pitch corrections.

In practice, this should make the quad feel:

- more controlled
- more locked-in
- less nervous
- better at correcting attitude
- more stable during fast direction changes

---

### 2. Less Twitchy Flight Feel

Very small 2-inch frames can feel extremely sharp, but also twitchy. The motors are close to the center, and the quad has low rotational inertia.

A slightly larger frame increases the rotational inertia of the quad. That means the quad resists unwanted angular changes a bit more.

The basic relationship is:

```text
angular acceleration = torque / moment of inertia
```

Or:

```text
α = τ / I
```

A higher moment of inertia makes the quad less twitchy and more predictable.

This does **not** mean the quad becomes slow, because the powertrain still uses small 2-inch props and high-KV motors. The frame calms the body down, while the motors and props keep the response fast.

The result should be:

```text
less twitchy than a normal 2-inch
but still much more responsive than a 3-inch
```

---

### 3. Better Component Protection

The longer arms help protect the important electronics.

Because the motors and arms sit farther away from the center stack, the frame creates a larger physical protection zone around:

- FC
- camera
- canopy
- wiring
- battery connector
- battery area

In crashes, the arms and motor area are more likely to take the first impact instead of the electronics.

This is especially useful on a very light quad, because the frame acts like a protective perimeter around the sensitive parts.

---

### 4. More Prop Clearance

The larger frame allows more prop flexibility than a normal compact 2-inch frame.

Supported / possible prop sizes:

| Prop Size | Status |
|---|---|
| 2.0 inch | Recommended |
| 2.2 inch low pitch | Good experimental option |
| 2.4 inch | Possible, but KV-dependent |
| 2.5 inch | Experimental, KV-dependent |

The frame is designed to physically allow larger prop options, but the main build philosophy is still focused on keeping prop inertia low.

---

## Design Philosophy

The design is based on a clear trade-off:

```text
Do not use the largest prop possible.
Use the largest useful performance while keeping response extremely fast.
```

Large props can give more efficiency, more glide, and more float, but they also have more rotational inertia.

More prop inertia means:

- slower spool-up
- slower spool-down
- less immediate throttle response
- more motor load
- more voltage sag
- more heat
- less direct stick feel

This quad avoids the slow prop-spool feeling that can happen on larger 1S 3-inch builds.

Instead, the preferred setup is:

```text
high-KV 1002 motors
+
lightweight 2-inch bi-blade props
+
larger 96 mm frame
```

This gives:

- fast prop response
- high RPM
- strong punch
- low prop inertia
- stable frame geometry
- locked-in feel
- less twitchy behavior

In short:

```text
Small prop for response.
High KV for punch.
Large frame for stability.
```

---

## 1002 Motor Theory

The motor size used in this build is **1002**.

This means approximately:

```text
10 mm stator diameter
2 mm stator height
```

A 1002 motor is very small and light. The benefits are:

- low motor weight
- low rotor inertia
- fast throttle response
- fast RPM changes
- very direct feel
- excellent for ultralight 1S builds

The downsides are:

- limited torque
- limited thermal mass
- limited continuous power
- high current draw at high KV
- easy to overload with large props

A 1002 motor is not meant to spin large 3-inch props aggressively. It is best suited for small, lightweight props where response matters more than cruise efficiency.

---

## 1S Electrical Theory

This build uses a **1S battery**, so voltage is limited.

Typical voltage:

```text
Nominal 1S LiPo: 3.7 V
Full 1S LiHV: 4.35 V
```

Motor no-load RPM is roughly:

```text
RPM = KV × voltage
```

For **25000KV**:

```text
25000 × 3.7 V = 92,500 RPM no-load
25000 × 4.35 V = 108,750 RPM no-load
```

For **22000KV**:

```text
22000 × 3.7 V = 81,400 RPM no-load
22000 × 4.35 V = 95,700 RPM no-load
```

These are no-load values. With a prop attached, real loaded RPM is much lower because of:

- prop load
- voltage sag
- motor torque limits
- battery current limit
- ESC losses
- aerodynamic drag

Realistic loaded RPM for the 25000KV 2-inch setup is expected to be around:

```text
~45,000–60,000 RPM
```

This is still extremely high for a micro quad and is one of the reasons the build should feel very aggressive.

---

## Prop Load Theory

Propeller load increases very quickly with diameter.

A simplified rule is:

```text
prop power demand ∝ diameter^4 to diameter^5 × RPM^3
```

This means a small increase in prop diameter can create a much larger increase in motor load.

Using 2.0 inch as a baseline:

| Prop Size | Diameter Ratio | Load Estimate Using D⁴ | Load Estimate Using D⁵ |
|---:|---:|---:|---:|
| 2.0" | 1.00x | 1.00x | 1.00x |
| 2.2" | 1.10x | 1.46x | 1.61x |
| 2.4" | 1.20x | 2.07x | 2.49x |
| 2.5" | 1.25x | 2.44x | 3.05x |
| 3.0" | 1.50x | 5.06x | 7.59x |

This explains why 2.4–2.5 inch props can become questionable on 25000KV 1002 motors.

Even if the prop physically fits, it may not make sense electrically or dynamically.

---

## Prop Inertia Theory

Responsiveness depends heavily on prop inertia.

The motor has to accelerate and decelerate the prop. For rotation:

```text
angular acceleration = motor torque / rotational inertia
```

Or:

```text
α = τ / I
```

A prop with lower rotational inertia can change RPM faster.

Prop inertia roughly depends on:

```text
I ≈ m × r²
```

Where:

- `m` = prop mass
- `r` = prop radius

A larger prop has more radius and usually more mass, so inertia increases quickly.

Compared to a 2-inch prop, a 3-inch prop has:

```text
3 / 2 = 1.5x diameter
```

Radius effect alone:

```text
1.5² = 2.25x inertia
```

But because the 3-inch prop is also heavier, real inertia can be several times higher.

That is why a 3-inch 1S quad often feels more floaty and less immediate.

This build avoids that by using small, lightweight bi-blade props.

---

## Why Bi-Blade Props?

Bi-blade props are preferred for this build.

Compared to tri-blades, bi-blades usually have:

- lower weight
- lower rotational inertia
- faster spool-up
- faster spool-down
- lower current draw
- better efficiency
- less voltage sag
- less motor heat
- longer flight time

On a high-KV 1S build, this matters a lot.

The motors are already spinning very fast and drawing high current. A heavier tri-blade would increase the load, reduce efficiency, create more sag, and make the motors run hotter.

The preferred prop style is:

```text
lightweight low-pitch bi-blade
```

Recommended options:

| Prop Type | Recommendation |
|---|---|
| 2.0" bi-blade | Best match |
| 2.2" low-pitch bi-blade | Good experimental option |
| 2.4" bi-blade | Better suited for lower KV |
| 2.5" bi-blade | Experimental, lower KV preferred |
| Tri-blade | Not preferred |

---

## GF2015 Prop Setup

The main prop choice is:

```text
Gemfan GF2015 bi-blade
```

This is a:

```text
2.0 inch diameter
1.5 pitch
2-blade prop
```

This prop fits the design goal well:

- low mass
- low inertia
- fast spool
- good thrust
- good efficiency
- high RPM capable
- suitable for aggressive 1S setups

The GF2015 is the main recommended prop for the 25000KV setup.

---

## 22000KV vs 25000KV

Known/expected thrust on GF2015:

| Motor KV | Thrust Per Motor | Total Thrust |
|---:|---:|---:|
| 22000KV | ~93 g | ~372 g |
| 25000KV | ~103 g | ~412 g |

Difference per motor:

```text
103 g - 93 g = 10 g
```

Difference total:

```text
10 g × 4 motors = 40 g
```

Relative difference:

```text
103 / 93 = 1.108
```

So 25000KV gives about:

```text
~11% more thrust
```

The trade-off is that 25000KV will likely have:

- higher current draw
- more voltage sag
- more heat
- shorter flight time
- more aggressive throttle response

The 22000KV version is still extremely strong, but easier on the battery and electronics.

---

## Thrust-to-Weight

Estimated AUW:

```text
~39–40 g
```

With 25000KV motors on GF2015:

```text
~103 g thrust per motor
```

Total thrust:

```text
103 g × 4 = 412 g
```

Thrust-to-weight:

```text
412 g / 40 g = 10.3:1
```

With 22000KV motors on GF2015:

```text
93 g × 4 = 372 g
```

Thrust-to-weight:

```text
372 g / 40 g = 9.3:1
```

Estimated thrust-to-weight comparison:

| Setup | Total Thrust | AUW | T/W |
|---|---:|---:|---:|
| 22000KV + GF2015 | ~372 g | ~40 g | ~9.3:1 |
| 25000KV + GF2015 | ~412 g | ~40 g | ~10.3:1 |

Both are extremely powerful for a 1S micro quad.

---

## Current Draw

The 25000KV setup can draw around:

```text
~12 A per motor
```

Total current at full throttle:

```text
12 A × 4 = 48 A
```

This is a lot for a 1S battery.

The LAVA 1S 580 mAh battery is a high-discharge pack, but full throttle is still a very heavy load for a single cell.

Expected behavior:

- short punch-outs should be possible
- long full-throttle runs are not recommended
- voltage sag is expected
- motor temperature should be checked
- ESC temperature should be checked
- battery temperature should be checked
- connector and wire temperature should be checked

Because the quad has such a high thrust-to-weight ratio, full throttle should rarely be needed.

This is important:

```text
The quad has more power than it usually needs.
The battery only sees peak load during short bursts.
```

---

## Prop Size Compatibility

The frame can physically support props larger than 2 inches, but the motor and KV choice determine what actually makes sense.

### Recommended Prop Sizes

| Motor KV | Prop Size | Recommendation |
|---:|---|---|
| 25000KV | 2.0" bi-blade | Ideal |
| 25000KV | 2.2" low-pitch bi-blade | Good experimental option |
| 25000KV | 2.4" bi-blade | Borderline / risky |
| 25000KV | 2.5" bi-blade | Not recommended |
| 22000KV | 2.0" bi-blade | Safe |
| 22000KV | 2.2" bi-blade | Good |
| 22000KV | 2.4" bi-blade | Testable |
| 22000KV | 2.5" bi-blade | Experimental |
| 1002 any KV | 3.0" | Not recommended for this concept |

---

## Why Not 3-Inch?

A 3-inch 1S build can be efficient, floaty, and smooth, but that is not the goal of this quad.

A 3-inch prop has much higher inertia and much higher load. It will not spool as quickly as a 2-inch prop.

The result is often:

- more glide
- more float
- better cruise efficiency
- slower response
- more lazy throttle feel
- less sharp stick response

This build is designed to avoid that.

The goal is not maximum prop size.

The goal is:

```text
maximum useful thrust
with minimum prop inertia
and maximum response
```

This is why the frame may physically support larger props, but the recommended setup stays around 2.0–2.2 inches.

---

## Comparison: This Build vs 1S 3-Inch 1202.5

A 1S 3-inch 1202.5 build usually uses:

- larger motors
- larger props
- lower KV
- more prop disc area
- more glide
- more efficiency at cruise
- more floaty flight feel

This build uses:

- smaller motors
- higher KV
- smaller props
- lower prop inertia
- lower AUW
- faster response
- more punch per gram

Comparison:

| Characteristic | This 2" 1002 Build | 1S 3" 1202.5 Build |
|---|---|---|
| Prop response | Very fast | Slower |
| Prop inertia | Low | Higher |
| Punch feel | Very aggressive | Strong but softer |
| Glide | Lower | Higher |
| Cruise efficiency | Good, but not main goal | Better |
| Stick feel | Sharp/direct | Smoother/floatier |
| AUW | ~39–40 g | Often ~50–60 g |
| Frame feel | Locked-in but responsive | Stable and floaty |
| Main goal | Response and punch | Efficiency and glide |

The 3-inch build may be better for relaxed cruising and longer flight time.

This 2-inch build should be better for:

- fast reaction
- punch-outs
- tight control
- quick direction changes
- aggressive flying
- low prop-spool delay

---

## Expected Flight Feel

The expected flight feel is:

```text
sharp
responsive
punchy
locked-in
less twitchy than a normal 2-inch
more aggressive than a 3-inch 1S cruiser
```

Expected characteristics:

- very fast throttle response
- minimal prop spool delay
- strong punch-outs
- high-pitched motor sound
- very low mass
- fast direction changes
- less twitchy than compact 2-inch frames
- more stable than typical 85 mm 2-inch frames
- less float than 3-inch 1S
- very high thrust-to-weight
- high current peaks

---

## Expected Sound

Because of the high KV and high RPM, this quad should have a very high-pitched sound.

It will not sound exactly like a 5-inch, because a 5-inch prop moves much more air and has a deeper sound.

However, the high RPM and fast spool should give this quad an aggressive micro scream.

Expected sound:

```text
high-pitched
sharp
angry
fast spool-up
mini race-drone character
```

---

## Estimated Speed

A realistic top speed estimate is:

```text
~90–120 km/h
```

Higher peaks may be possible with:

- fresh LiHV battery
- good tune
- low drag build
- full throttle burst
- favorable wind
- clean prop condition

But top speed is not the main design goal.

The main design goals are:

- response
- punch
- control
- locked-in feel
- low AUW

---

## Motor Dampers

The build uses four custom 3D printed motor dampers.

Per damper:

```text
Area: 44 mm²
Thickness: 0.5 mm
```

Volume per damper:

```text
44 mm² × 0.5 mm = 22 mm³
```

For four dampers:

```text
22 mm³ × 4 = 88 mm³
```

Convert to cubic centimeters:

```text
88 mm³ = 0.088 cm³
```

With typical 3D print material density around 1.2 g/cm³:

```text
0.088 cm³ × 1.2 g/cm³ = 0.106 g
```

Estimated total weight:

```text
~0.1 g
```

The motor dampers add almost no weight, but may help isolate vibration between the motors and frame.

---

## FC Protector

The final FC protector area is:

```text
347 mm²
```

Assuming 0.5 mm thickness:

```text
347 mm² × 0.5 mm = 173.5 mm³
```

Convert to cubic centimeters:

```text
173.5 mm³ = 0.1735 cm³
```

With 3D printed material around 1.2–1.27 g/cm³:

```text
~0.21–0.22 g
```

Estimated FC protector weight:

```text
~0.2 g
```

This is a very small weight penalty for extra protection.

---

## Battery

Planned battery:

```text
BETAFPV LAVA 1S 580 mAh LiHV
```

Estimated battery weight:

```text
~14.1 g
```

Estimated AUW with this battery:

```text
dry weight ~25–26 g
battery ~14.1 g
total ~39–40 g
```

---

## Strengths

This build should be strong in:

- throttle response
- punch
- fast RPM changes
- low prop-spool delay
- low AUW
- high thrust-to-weight
- control authority
- locked-in frame feel
- component protection
- aggressive 1S performance

---

## Trade-Offs

The design is not optimized for maximum flight time or smooth cruising.

Expected trade-offs:

- high current draw
- voltage sag during hard punch-outs
- motor heat if over-propped
- battery stress at full throttle
- less glide than 3-inch
- less cruise efficiency than larger prop setups
- tune may need care because of high power and low mass

This is a performance-focused 1S build, not a relaxed cruiser.

---

## Recommended Testing Procedure

When testing new props or motor KV combinations:

1. Start with short hover tests.
2. Check motor temperature after 20–30 seconds.
3. Check battery temperature.
4. Check ESC temperature.
5. Do short punch-outs only.
6. Watch voltage sag.
7. Avoid long full-throttle runs at first.
8. Review blackbox if available.
9. Increase throttle load gradually.
10. Stop testing if motors become too hot to touch.

Recommended first setup:

```text
1002 25000KV
GF2015 bi-blade
1S LiHV
throttle limit optional
```

Optional safer initial Betaflight setup:

```text
Throttle limit: 85–90%
```

This can reduce current spikes while still keeping the quad very fast.

---

## Recommended Build Direction

Best match for the design goal:

```text
1002 25000KV
GF2015 2-inch bi-blade
1S LAVA 580 mAh
96 mm carbon frame
~40 g AUW
```

This gives the most aggressive version of the concept.

More efficient / safer version:

```text
1002 22000KV
GF2015 or 2.2-inch low-pitch bi-blade
1S LAVA 580 mAh
96 mm carbon frame
~40 g AUW
```

Experimental larger-prop version:

```text
1002 22000KV
2.4-inch bi-blade
careful temperature testing required
```

Not recommended for the main goal:

```text
25000KV + 2.5-inch
1002 + 3-inch
heavy tri-blades
long full-throttle runs
```

---

## Final Summary

This quad is designed around a very specific theory:

```text
Use the smallest prop that can still make serious thrust.
Use high KV to create punch and RPM.
Use low prop inertia to keep response instant.
Use a larger frame to make the quad less twitchy and more locked-in.
Keep the whole build extremely light.
```

The result should be a 1S quad that feels:

- much more responsive than a 3-inch 1S build
- less twitchy than a compact 2-inch build
- more locked-in than a normal toothpick
- extremely punchy for its size
- very light
- very aggressive
- very fun

In one sentence:

> **A 96 mm 1S 2-inch high-KV toothpick designed for instant response, extreme punch, and a larger-quad locked-in feel without the lazy spool of bigger props.**
