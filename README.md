# bodegraph
A few small modifications to Robert Papanicola's BodeGraph package.
- Fixed a bug where `\POAmpAsymp{a}{b}` generages a blank plot for b >= 2.
- Modified `\POArgAsymp` to change slopes a decade before and after a pole/zero.
- Modified `\SOArgAsymp` to change slopes at ω<sub>n</sub>/10<sup>ζ</sup> and 10<sup>ζ</sup>ω<sub>n</sub>.

* Call `\BodeGraph` with the option `samples=300` (or more, as needed) to get accurate asymptotic phase plots.
