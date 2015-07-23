
# Estimate parameters for Beta Distribution 

estBetaParams <- function(mu, V) {
  alpha <- ((1 - mu) / V - 1 / mu) * mu ^ 2
  beta <- alpha * (1 / mu - 1)
  return(params = list(alpha = alpha, beta = beta))
}
