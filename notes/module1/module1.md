# Circuit Theory
## Assumptions
| Assumptions          | Description                                                   |
|-----------------------|---------------------------------------------------------------|
| **Lumped Parameter System** | If a circuit is small enough.                                |
| **Net Charge is Zero**   | No component can collect a net excess of charge.              |
| **Magnetic Coupling**    | There is no magnetic coupling between components.             |
## Charge, Voltage, and Current
- Charge is Discrete
    $ q = 1.602\times10^{-19}C $
- Charge is Bipolar
- Separation of Charge => Voltage
    $$
    V = \frac{dw}{dq}
    $$
- Motion of Charge => Current
    $ i = \frac{dq}{dt} $
## Power and Energy
- Power is the rate at which work is done.
$$
 p = \frac{dw}{dt} = (\frac{dw}{dq})(\frac{dq}{dt}) = vi
$$
- Work Energy is the integral of power
    $$
    w = \int{pdt}
    $$
## The Passive Sign Convention
Given a two terminal element, with a differential voltage across it and a
current. This implies current flow. You can calculate power simply, with
$$  p = iv $$

If Current is flowing in the opposite direction, that is, from - to +, 
current is calclulated as:

$$ p = -iv $$

The direction of the current flow must always be paid attention to.

- If Power is positive, this indicates that there has been a dissipation of
energy. It has been delivered to the device or element and vice versa.

### Example 1
Given 2 Car batteries, both with 12V at opposite polarities, that is, 
the positive terminal is connected to the positive and negative to negative.

If current is flowing from one battery to another, you can measure the current
traveling from one to the other.

If 50A are running through the cables from battery 2 to 1, we can:
$ P_{batt 1} = (12V)(50A) = 600W $
But if we are calculating the opposite battery, we must:
$ P_{batt 2} = -(12V)(50A) = -600W $

This is all dependandant on the *reference* however. If we calculate the
reference as -12V, the same math occurs, but with negative signs.
