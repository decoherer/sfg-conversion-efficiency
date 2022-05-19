SFG conversion efficiency measurement
-------------------------------------

Here are several different ways to calculate the SFG conversion
efficiency in the waveguide. We assume that λ<sub>1</sub> is the pump wavelength
(e.g. 1550 nm), λ<sub>2</sub> is the input signal wavelength (e.g. 920 nm), and
λ<sub>SFG</sub> is the output SFG wavelength (e.g. 580 nm).

**1. Low power limit (the standard way)**

*η<sub>SFG</sub>* = P<sub>SFG</sub> / (P<sub>1</sub>× P<sub>2</sub>),

where the powers are the output powers and P<sub>SFG</sub> is much less than P<sub>1</sub>
and P<sub>2</sub> (less than 10% for both for \~10% accuracy).

**2. 100% photon conversion**

*η<sub>SFG</sub>* = (λ<sub>2</sub>/λ<sub>SFG</sub>) × π<sup>2</sup> / (4 P<sub>1</sub>),

Valid when the pump power P<sub>1</sub> is increased to the point at which P<sub>SFG</sub>
is maximized, which is also the same as the point at which P<sub>2</sub> is
minimized to zero. It is required that the pump power P<sub>1</sub> has less than
10% depletion.

**3. Re-emergent 100% photon conversion**

*η<sub>SFG</sub>* = *m*<sup>2</sup> × (λ<sub>2</sub>/λ<sub>SFG</sub>) × π<sup>2</sup> / (4 P<sub>1</sub>),

where *m* is an odd number. Pump power P<sub>1</sub> is increased past the point
at which P<sub>SFG</sub> is maximized until it is zeroed and then maximized again
at 9× the original power, then this formula can be used with *m* = 3.
(Similarly, *m* = 5 for 3rd maximum, *m* = 7 for 4th maximum, etc.)
Must have less than 10% depletion in P<sub>1</sub>. Also works at the points
where P<sub>SFG</sub> is zero for even *m*, for instance, *m* = 2 for 2nd zero
(1st zero after 1st maximum), *m* = 4 for 3rd zero, etc. Since
there is no depletion of P<sub>1</sub> at the zero point, the even *m*
measurements are valid even for high P<sub>1</sub> depletion conditions.

**4. Small P<sub>2</sub> depletion**

*η<sub>SFG</sub>* = (λ<sub>2</sub>/λ<sub>SFG</sub>) × γ / P<sub>1</sub>,

where γ is the amount of depletion at λ<sub>2</sub>,

γ = 1 - (P<sub>2</sub> in the presence of P<sub>1</sub>)÷(P<sub>2</sub> in the absence of P<sub>1</sub>).

Instead of turning P<sub>1</sub> on and off to measure P<sub>2</sub>, it is even better to
tune λ<sub>1</sub> on and off of peak phase matching. Must have less than 10%
depletion in P<sub>2</sub> and even less in P<sub>1</sub>.

**5. Arbitrary P<sub>2</sub> depletion**

*η<sub>SFG</sub>* = (λ<sub>2</sub>/λ<sub>SFG</sub>) × (sin<sup>-1</sup>
√\[(λ<sub>SFG</sub>/λ<sub>2</sub>)×(P<sub>SFG</sub>/P<sub>2</sub>)\])<sup>2</sup> / P<sub>1</sub>.

This is exact for any amount of P<sub>2</sub> depletion up to 100%, however this
formula still requires that the pump depletion P<sub>1</sub> is small. This
formula can be used to derive the alternative forms above. This equation
can be rewritten as:

P<sub>SFG</sub> = P<sub>2</sub> × (λ<sub>2</sub>/λ<sub>SFG</sub>) × sin<sup>2</sup>
√\[(λ<sub>SFG</sub>/λ<sub>2</sub>)×P<sub>1</sub>×*η<sub>SFG</sub>*\].

**6. SFG in the presence of loss**

If there is loss in the waveguide, the output SFG power is reduced.
Instead of P<sub>SFG</sub> = P<sub>1</sub> × P<sub>2</sub> × *η<sub>SFG</sub>* in the low power limit, we
have:

P<sub>SFG</sub> = P<sub>1</sub> × P<sub>2</sub> × *η<sub>SFG</sub>* × 10<sup>-0.1(α<sub>1</sub> + α<sub>2</sub> + α<sub>SFG</sub>)L/2</sup>,

where α<sub>1</sub>, α<sub>2</sub>, α<sub>SFG</sub> are the losses in dB/cm at each of the
wavelengths λ<sub>1</sub>, λ<sub>2</sub>, λ<sub>SFG</sub>. For instance, if the loss is 0.1 dB/cm
at each wavelength and the length is 4 cm, then the total loss in
conversion is 3 × 0.1 dB/cm × 4 cm ÷ 2 = 0.6 dB and the effective
conversion efficiency is 10<sup>-0.06</sup> = 87% of the theoretical conversion
efficiency.

Note that there are other ways that upconversion efficiency can be
defined. It is defined here so that it is obvious and useful in the low
power limit (*η<sub>SFG</sub>* = P<sub>SFG</sub> / (P<sub>1</sub>× P<sub>2</sub>)). Another way that even
some textbooks use is the SHG-equivalent conversion efficiency:

*η<sub>SHG-equivalent</sub>* = *η<sub>SFG</sub>* ÷ 4.

Another way it can be defined is as the photon conversion efficiency:

*η<sub>photon</sub>* = (λ<sub>SFG</sub>/λ<sub>2</sub>) × *η<sub>SFG</sub>*

which can be thought of as the percent of the number of photons
converted per unit of pump power, and is seen alternatively to Equation
2 as *η<sub>photon</sub>* = π<sup>2</sup> / (4 P<sub>1</sub>).

SHG conversion efficiency measurement
-------------------------------------

λ is the pump wavelength (e.g. 1064 nm) with output power P and λ<sub>SHG</sub>
is the SHG wavelength (e.g. 532 nm) with output power P<sub>SHG</sub>.

**1. Low power limit (the standard way)**

*η<sub>SHG</sub>* = P<sub>SHG</sub> / P<sup>2</sup>,

where the powers are the output powers and P<sub>SHG</sub> is much less than P
(less than 10% for \~10% accuracy).

**2. Arbitrary pump depletion**

*η<sub>SHG</sub>* = (tanh<sup>-1</sup> √\[P<sub>SHG</sub>/P\])<sup>2</sup> / P.

This is exact for any amount of depletion. This formula is equivalent to
Equation 1 at low power. This equation can be rewritten as:

P<sub>SHG</sub> = P × tanh<sup>2</sup> √\[P×*η<sub>SHG</sub>*\]

**3. Multimode pump**

*η<sub>SHG</sub>* = ½ P<sub>SHG</sub> / P<sup>2</sup>,

where the factor of two is due to the fact that for a
multi-longitudinal-mode pump there is both SFG and SHG occurring among
multiple lines. (The figure is from Helmfrid and Arvidsson,
Second-harmonic generation in quasi-phase-matching waveguides with a
multimode pump (1991).)

![](./media/image1.emf){width="4.0in" height="3.64741469816273in"}

**4. SHG in the presence of loss**

Let's consider a few different cases for calculating the internal
(*η*<sub>I</sub>) and external (*η*<sub>E</sub>) conversion efficiency in the presence of
loss, based on where we assume the loss to be.

T = pump transmission

P = measured output pump power

P<sub>SHG</sub> = measured output SHG power

*η* = P<sub>SHG</sub> / P<sup>2</sup> = conversion efficiency as normally measured using
output powers

External conversion efficiency, based on pump power at input and SHG
power at output, is what really matters for a device and will always be
equal to T<sup>2</sup>*η* no matter where the losses are coming from.

*η*<sub>E</sub> = T<sup>2</sup> × *η*

Internal conversion efficiency is the theoretically expected conversion
efficiency that you would get if all the losses were eliminated, which
we calculate differently from the measurements depending on where the
loss is coming from. Here are six different scenarios:

A.) Assume all loss is at input (no loss at output, no propagation
loss). This is what we normally assume, which seems pretty fair for
short chips considering that we expect mode match loss at the input but
not output:

*η*<sub>I</sub> = *η*

B.) Assume all loss is at output (no loss at input, no propagation
loss), and that SHG loss is the same as pump loss:

*η*<sub>I</sub> = T × *η*

C.) Assume input and output losses are equal, T<sub>IN</sub> = T<sub>OUT</sub> = √T, and
are the same for SHG and pump (no propagation loss).

*η*<sub>I</sub> = √T × *η*

D.) Assume all loss is propagation loss (no loss at input or output),
and is the same for SHG and pump. Then T = 10<sup>-0.1αL</sup> where α is the
propagation loss in dB/cm and L is the chip length.

*η*<sub>I</sub> = √T × *η*

E.) Assume all loss is at input except for Fresnel loss, T<sub>F</sub>, at output
(no propagation loss). T = T<sub>IN</sub> × T<sub>F</sub>. For free-space coupling, T<sub>F</sub> =
(*n*-1)²/(*n*+1)² where *n* is the index. (T<sub>F</sub> = 92% for KTP. T<sub>F</sub> =
86% for LN.)

*η*<sub>I</sub> = T<sub>F</sub> × *η*

F.) General case, T = T<sub>IN</sub> × T<sub>P</sub> × T<sub>OUT</sub>, assuming pump and SHG
losses are the same. The propagation loss is T<sub>P</sub> = 10<sup>-0.1αL</sup> where α
is the propagation loss in dB/cm and L is the chip length.

*η*<sub>I</sub> = √T<sub>P</sub> × T<sub>OUT</sub> × *η*

DFG conversion efficiency
-------------------------

Rough notes for now:

Assume P'<sub>1</sub> at 100% photon conversion point. Then for λ<sub>2</sub>→λ<sub>3</sub> in
presence of P'<sub>1</sub> (from Eq. 2 above):

*η* = (λ<sub>2</sub>/λ<sub>3</sub>) × π<sup>2</sup> / (4 P'<sub>1</sub>) where P<sub>3</sub> = P<sub>1</sub> × P<sub>2</sub> × *η* for
low power SFG

Similarly, for λ<sub>3</sub>→λ<sub>2</sub> in presence of P<sub>1</sub>:

*η* = (λ<sub>3</sub>/λ<sub>2</sub>) × π<sup>2</sup> / (4 P'<sub>1</sub>) where P<sub>2</sub> = P<sub>1</sub> × P<sub>3</sub> × *η* for
low power DFG

First one is SFG, second one is DFG, therefore:

(λ<sub>3</sub>/λ<sub>2</sub>) × *η*<sub>SFG</sub> = (λ<sub>2</sub>/λ<sub>3</sub>) × *η*<sub>DFG</sub>

*η*<sub>DFG</sub> = (λ<sub>3</sub>/λ<sub>2</sub>)<sup>2</sup> × *η*<sub>SFG</sub>

Quantum frequency conversion
----------------------------

QE = sin²√\[ η<sub>SFG</sub> L² P<sub>1</sub> (λ<sub>3</sub>/λ<sub>2</sub>) \]

P<sub>3</sub> = P<sub>2</sub> (λ<sub>3</sub>/λ<sub>2</sub>) sin²√\[ η<sub>SFG</sub> L² P<sub>1</sub> (λ<sub>3</sub>/λ<sub>2</sub>) \]

Estimate QE with output loss of λ<sub>3</sub>:

QE = sin²√(ηL²P<sub>1</sub>(λ<sub>3</sub>/λ<sub>2</sub>)) × 10<sup>-(loss/10)L/2</sup>
