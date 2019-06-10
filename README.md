# FizzBuzz-Perl
# Fizzbuzz Project 2 in Perl

use strict;
use warnings;
use diagnostics;
use feature 'say';
for (my $x = 0; $x < 101; x++) {
  if ($x % 15 === 0) {
    say ("Fizzbuzz");
  }
  if ($x % 3 === 0) {
    say ("Fizz");
  }
  elseif ($x % 5 === 0) {
    say ("Buzz";)
  }
  else {
    say ("$x");
  }
}
