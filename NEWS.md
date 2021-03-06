# LineSearches v0.1.5 release notes
* Fix bug in `bt3!` linesearch, which uses the wrong initial step in the first cubic interpolation. See 
[#29](https://github.com/anriseth/LineSearches.jl/pull/29)

# LineSearches v0.1.4 release notes
* Adds the `basic!` linesearch, which simply takes a predefined step. See
[#26](https://github.com/anriseth/LineSearches.jl/pull/26)

# LineSearches v0.1.3 release notes
* Algorithms morethuente and strongwolfe now takes an initial step length as an input
[#23](https://github.com/anriseth/LineSearches.jl/pull/23)
* The backtracking algorithm now performs quadratic or cubic interpolations
[#20](https://github.com/anriseth/LineSearches.jl/pull/20)

# LineSearches v0.1.1 release notes
* Hagerzhang and Backtrack now throw LineSearchExceptions
[#19](https://github.com/anriseth/LineSearches.jl/pull/19)

# LineSearches v0.1.0 release notes
* Breaking: Algorithms have been renamed [#16](https://github.com/anriseth/LineSearches.jl/pull/16)
* Added Backtracking with quadratic interpolation [#7](https://github.com/anriseth/LineSearches.jl/pull/7)
