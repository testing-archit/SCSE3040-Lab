# Task T2 --- Does the split change the answer?

The 70/30 split with seed 7 gave a linear regression test MAE of 2.10 minutes,
close to the 1.92-minute MAE from the original 80/20 split with seed 42, so
the conclusion --- that the model beats the roughly 10-minute baseline by a
wide margin --- did not change. The two splits agreeing to within about a
fifth of a minute suggests this result was not a lucky draw, but a single
comparison like this is still not proof of stability, so I would only fully
trust the number after seeing it hold up across several different splits
(cross-validation), which is exactly what Practical 03 does next.
