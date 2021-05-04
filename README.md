# The only purpose of this package is to silence the Nemo.jl welcome message

The entire content of this package is
```julia
module NoBannerNemo
    function __init__()
        ENV["NEMO_PRINT_BANNER"] = "false"
    end
end
```
