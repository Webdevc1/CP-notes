# Sieve of Erastosthenes (SOE1)

This is a simple method to find the prime numbers upto a certain number.

    The Time Complexity is O(n ln ln n).

SOE1 revolves around the idea of ``creating a boolean or char vector of size n`` (where n is the number till whuich we need to find the prime numbers), and using 2 or 3 values, to precompute
what numbers are prime and what are composites.

The basic idea (here I am using a boolean vector) to first fill the vector as true, except for 0 and 1 (Neither primes nor composites), then loop through the vector denoting
the multiples of the prime numbers as composites (marking them as false). Hence at the end only the prime numbers remain marked as ``true``.


The link to the my notes is here:
``https://wbd.ms/share/v2/aHR0cHM6Ly93aGl0ZWJvYXJkLm1pY3Jvc29mdC5jb20vYXBpL3YxLjAvd2hpdGVib2FyZHMvcmVkZWVtLzA2NWM3NDg2NzYzZDQyOWY4MWE4ZTIxZGU0MjA2N2ExX0JCQTcxNzYyLTEyRTAtNDJFMS1CMzI0LTVCMTMxRjQyNEUzRF8zNDEzODBiMC1hYmFhLTQ0NWYtODc5Yi1hZmFjMWQ5YjgyM2E=``
