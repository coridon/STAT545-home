You can see the glorious result of all this by visiting the `foofactors` package on GitHub: <https://github.com/jennybc/foofactors>.

back to [All the package things](packages00_index.html)

#> [38ed51b] 2015-11-23: Initial commit
Your most recent commit should look something like this (if you're lucky, you've got a nicer way of inspecting it):
#> [39cb828] 2015-11-23: Add fbind()
#> diff --git a/R/fbind.R b/R/fbind.R
#> new file mode 100644
#> index 0000000..7b03d75
#> --- /dev/null
#> +++ b/R/fbind.R
#> @@ -0,0 +1,3 @@
#> +fbind <- function(a, b) {
#> +  factor(c(as.character(a), as.character(b)))
#> +}
#>   '/var/folders/vt/4sdxy0rd1b3b65nqssx4sx_h0000gn/T//RtmpX4V9Xx/foofactors_0.0.0.9000.tar.gz'  \