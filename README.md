# skiplist
A skiplist implementation in `C++`.

# Usage

Compile an executable `skiplist` by

```bash
$ make
```

Use:

```bash
$ ./skiplist input.txt output.txt
```

to take `input.txt` and output to `output.txt`.

`output.txt` will contain the words in an alphabetical order in the input file with frequency and pages of occurrences. 

# Example Output

An example output of [`advert.txt`](http://textfiles.com/fun/advert.txt) is:

```
a (27) 1-5
abilities (1) 4
ability (1) 5
about (3) 1,3
access (1) 5
account (3) 3-4
additionally (1) 1
advertising (14) 1-5
again (1) 4
age (1) 1
agencies (12) 1-4
agency (19) 1-5
agency's (2) 4
aggressive (1) 2
all (6) 1-3,5
all-text (1) 5
allow (1) 1
alphabetically (1) 3
also (1) 4
an (8) 1-4
and (28) 1-5
another (3) 2,5
any (1) 1
approach (2) 3-4
arcane (1) 5
are (6) 2-5
as (6) 1,3,5
asked (1) 4
assignment (1) 4
assignments (2) 4
assuming (1) 3
at (8) 1-5
attention (2) 3
author (1) 5
available (2) 2-3
avoid (1) 1
avoiding (1) 4
awarding (1) 4
b (1) 5
back (1) 1
based (1) 5
basic (1) 1
bbs (1) 5
be (22) 1-5
because (1) 2
been (1) 4
begin (1) 3
being (1) 3
beneficial (1) 1
best (3) 1-2
better (1) 2
between (1) 1
big (2) 3,5
bill (1) 3
bloomingdale (1) 5
book (1) 2
both (2) 3-4
brief (1) 3
briefing (1) 4
bring (1) 3
broader (1) 4
brother (1) 5
budget (3) 1-3
burn (1) 5
business (9) 1-3
but (1) 2
by (3) 1-2
call (1) 3
callers (1) 5
calls (4) 1-3
can (10) 1-5
candidate (1) 2
candidates (7) 3-4
carefully (1) 4
case (1) 1
caution (1) 1
certain (3) 1,5
chances (1) 4
changes (1) 4
charm (1) 4
choice (2) 1
choices (1) 5
choose (1) 1
choosing (1) 1
class (1) 4
client-agency (3) 1,4
clients (2) 3-4
collecting (1) 3
come (1) 3
commitment (3) 1,5
communication (1) 1
companies (1) 2
company (2) 2
completed (1) 4
comprehensive (1) 3
compromise (1) 1
concerned (2) 1,3
confidential (1) 2
confidentially (1) 2
consider (1) 4
consultant (1) 5
contact (3) 3,5
contenders (1) 4
continue (1) 5
contract (1) 1
control (1) 2
conversations (1) 5
cost (1) 4
costs (1) 4
could (1) 1
creativity (1) 3
criteria (1) 1
current (1) 3
data (2) 3,6
day (2) 4
deadlines (1) 1
dealing (1) 4
decision (2) 1,5
decision-making (1) 2
decisions (1) 1
difficult (1) 1
directly (1) 1
directory (4) 2-3
disclaimer (1) 5
discretion (1) 2
discussions (2) 4
diversive (1) 5
do (3) 1-2
doing (3) 2,4
don (1) 1
don't (4) 1,3-5
donald (1) 5
done (4) 2-4
down (1) 3
downloaded (1) 5
drive (1) 5
during (1) 4
each (3) 1,3-4
easy (1) 5
effective (1) 2
eight (2) 1,3
electron (1) 5
else (1) 2
enhance (1) 5
even (1) 4
example (3) 2-3
exercise (1) 1
exist (1) 2
expect (2) 1,5
expensive (1) 1
experience (1) 3
explosives (1) 5
extremism (1) 5
factor (1) 3
fairly (1) 3
fax (1) 5
feel (1) 2
field (5) 1-3
file (1) 5
final (1) 4
finally (1) 5
find (5) 1-2,4
finding (1) 3
finish (1) 1
first (3) 2-4
first-time (1) 5
fish (1) 3
flag (1) 5
followed (1) 5
for (19) 1-6
fortran (1) 5
four (1) 3
fourth (1) 3
freen (1) 5
fresh (1) 3
friday (1) 2
from (7) 1,3-5
full (1) 5
further (1) 3
future (2) 1,4
games (1) 2
geographical (1) 2
geographically (1) 3
get (7) 2-4
gets (1) 5
getting (1) 2
give (2) 3-4
go (1) 2
goals (1) 1
good (3) 2-3
governing (1) 3
graduated (1) 4
group (1) 4
hand (1) 2
handle (1) 1
handled (1) 3
have (7) 1,3-5
he (1) 1
head (1) 5
help (1) 1
helpful (1) 2
here (1) 1
high (1) 5
hillsborough (1) 5
hopefully (3) 3-4
how (5) 3-4
hunter (1) 5
identify (2) 2
if (8) 1-5
il (1) 2
important (2) 2-3
in (19) 1-5
include (1) 3
inconvenience (1) 4
influence (1) 1
information (6) 2-3,5
insane (1) 5
investigation (1) 5
involved (1) 1
irrelevant (1) 2
is (25) 1-5
it (11) 1-5
it's (1) 3
jeff (1) 5
job (1) 2
just (1) 2
keep (1) 2
key (1) 3
know (3) 4-5
knowledge (1) 5
kobes (2) 1,5
leadership (1) 1
leads (1) 2
learn (1) 4
learned (1) 5
least (2) 1,5
leaving (1) 3
let (1) 4
library (1) 2
lies (1) 5
like (3) 1,3-4
list (5) 3-4
listing (2) 2-3
lists (1) 3
little (1) 2
live (1) 5
local (2) 2
long (1) 4
look (3) 2,4
looking (1) 4
looks (1) 3
lose (2) 2,4
lots (1) 4
luck (1) 3
mail (1) 3
make (4) 1,3,5
making (1) 1
manager (1) 1
many (2) 2,4
marketing (2) 1,5
marriage (3) 1
may (7) 1-5
means (1) 1
media (1) 2
meetings (3) 4-5
mick (1) 5
monday (1) 2
more (2) 2,5
most (1) 1
much (1) 3
must (3) 1,3-4
mutual (3) 1,4
mutually (1) 1
names (2) 2-3
narrow (3) 3-4
narrowed (2) 3-4
narrowing (1) 3
national (1) 2
need (5) 2-3
needs (2) 1
negotiate (1) 1
nerves (1) 6
never (1) 4
new (2) 2
next (1) 4
nirvananet (1) 5
nj (1) 5
no (1) 1
nobody (1) 5
not (4) 2-3,5
note (1) 1
noticed (1) 3
now (4) 1,4-5
number (2) 2,5
object (1) 3
objective (1) 3
objectives (1) 5
obscure (1) 5
of (33) 1-5
office (1) 3
often (1) 1
old (1) 2
on (4) 2,4-5
once (1) 3
one (3) 1-2
ones (1) 3
or (9) 1-5
orchard (1) 2
order (1) 3
other (3) 1-3
out (3) 2,4
own (1) 2
paid (3) 2,4
partner (3) 1
partners (2) 1,5
partnership (1) 3
pay (2) 1,3
people (4) 1-2,4
performance (1) 5
person (1) 4
personality (1) 2
personnel (1) 4
philosophy (1) 1
phone (6) 2-5
pick (1) 4
picture (1) 4
piece (1) 3
pieces (1) 2
plan (1) 5
poindexter (1) 5
political (1) 5
pond (1) 3
possible (2) 2-3
possibly (1) 2
practical (1) 1
premature (1) 2
prepared (2) 1
present (1) 4
preview (1) 4
principals (1) 3
problematic (1) 1
problems (1) 4
procedure (1) 1
process (2) 1-2
produce (1) 4
professional (3) 1-2
program (2) 1
promised (1) 5
propel (1) 1
proposals (1) 2
provide (2) 2-3
provides (1) 3
publication (1) 2
published (1) 2
publishing (1) 2
pursuit (1) 2
quickly (1) 3
ranked (2) 3
rat (1) 5
rates (1) 1
ratsnatcher (1) 5
raw (2) 6
re-training (1) 4
reach (1) 4
realitycheck (1) 5
received (1) 3
region (1) 2
register (1) 2
regular (1) 5
related (1) 5
relationship (2) 1
remain (1) 2
remember (2) 3-4
represent (2) 3-4
representative (1) 2
representatives (1) 2
resources (1) 3
response (1) 3
returned (1) 3
revealing (1) 2
reviews (1) 5
right (3) 1-2,5
road (1) 2
round (1) 4
rumours (1) 5
run (1) 1
running (1) 3
sales (1) 2
same (2) 5
schematic (1) 5
school (1) 4
screaming (1) 5
search (1) 3
second (1) 2
see (1) 4
select (1) 5
selecting (1) 1
selection (4) 1-4
selling (1) 2
serious (1) 4
services (2) 1-2
set (1) 1
sexuality (1) 5
share (1) 5
she (1) 1
shop (2) 3
short-timers (1) 4
should (3) 1,3-4
signal (1) 4
similar (2) 1,4
simple (1) 3
situation (1) 1
six (2) 1,3
size (5) 2-3
skokie (1) 2
small (1) 3
solicitations (1) 2
some (4) 1,3-4
someone (1) 4
sometimes (1) 4
sounds (1) 3
source (2) 2
speak (2) 1,4
specializing (1) 5
speculation (1) 5
spoke (1) 2
stage (2) 4
stale (1) 3
standard (2) 2-3
start (2) 1-2
started (1) 2
step (1) 4
steps (1) 1
stone (1) 1
story (1) 5
subjects (1) 5
success (2) 1
successful (2) 1,3
surprises (1) 1
surveying (1) 2
swamped (1) 2
swayed (1) 4
systems (1) 5
table (1) 3
talk (1) 4
team (1) 4
telephone (1) 5
tell (1) 4
temple (1) 5
test (1) 4
th (1) 3
that (6) 1,3-5
the (64) 1-5
their (4) 1-2,4
them (4) 3-5
then (1) 2
these (6) 2,4
they (5) 3-4
they're (1) 2
this (23) 1-5
those (2) 1-2
three (1) 3
tie-breaker (1) 5
time (2) 3-4
time-wasting (1) 2
tips (1) 1
tm (1) 5
to (44) 1-5
try (2) 1,4
two (3) 2,4
unlikely (1) 1
unlimited (1) 5
up (2) 3-4
use (1) 3
usually (1) 1
very (1) 2
viewpoints (1) 3
visits (1) 4
want (2) 2,5
wants (1) 2
way (2) 1-2
we (2) 5
weeks (1) 1
what (5) 2,4-5
when (4) 1,3-4
where (2) 2,5
who (6) 1-5
who's (1) 2
whole (1) 5
whose (1) 3
wild (1) 5
will (9) 1-5
win (1) 4
wishes (1) 1
with (10) 1-4
without (3) 1-3
words (1) 2
work (8) 1-4
working (1) 3
works (1) 3
worth (1) 4
would (3) 2,4-5
write (1) 2
wrong (1) 1
x (4) 5-6
you (43) 1-5
you'd (1) 2
you'll (2) 3-4
you're (1) 4
your (28) 1-5
zardoz (1) 5
```



