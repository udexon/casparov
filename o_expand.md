
```
$ php hgm.php 'a b + c d + *' space: explode: hgm: stk: t: nl: exp3: 6 subt: 5 subt: 
: top_edges t t2sn: cx: over: cx: 1 - i: e ix: \; top_edges 
: left_terms dup: 1 ix: 5 pick: swap: i: e i: dup: 0 i: subt: over: 1 i: subt: \; \ 
"left edges terms" . 
left_terms 3 pick: 0 i: subt: \\* 1 pick: 4 pick: \\* \\+ 7 mss: s:

fgl_s 397 < 10 > array ( 0 => 'd c + b a + *', 1 => 'd c +', 
2 => array ( 0 => array ( 'v' => 'a', ), 1 => array ( 'v' => 'b', ), 
2 => array ( 'v' => '+', 't' => 'oa', 'e' => array ( 0 => 1, 1 => 0, ), ), 
3 => array ( 'v' => 'c', ), 4 => array ( 'v' => 'd', ), 
5 => array ( 'v' => '+', 't' => 'oa', 'e' => array ( 0 => 4, 1 => 3, ), ), 
6 => array ( 'v' => '*', 't' => 'om', 'e' => array ( 0 => 5, 1 => 2, ), ), ), 
3 => 7, 
4 => array ( 'v' => '*', 't' => 'om', 'e' => array ( 0 => 5, 1 => 2, ), ), 
5 => array ( 0 => 5, 1 => 2, ), 
6 => array ( 0 => 5, 1 => 2, ), 
7 => array ( 0 => 1, 1 => 0, ), 
8 => 'b', 
9 => 'a d c + \\* d c + b \\* \\+', )





$ php hgm.php 'a b + c *' space: explode: hgm: stk: t: nl: 
: top_edges t t2sn: cx: over: cx: 1 - i: e ix: \; top_edges 
: left_terms dup: 1 ix: 5 pick: swap: i: e i: dup: 0 i: subt: over: 1 i: subt: \; \ "left edges terms" . 
left_terms 3 pick: 0 i: subt: \\* 1 pick: 4 pick: \\* \\+ 7 mss: s:

fgl_s 397 < 9 > array ( 0 => array ( 0 => 'hgm.php', 1 => 'a b + c *', 
2 => 'space:', 3 => 'explode:', 4 => 'hgm:', 5 => 'stk:', 6 => 't:', 7 => 'nl:', 8 => ':', 9 => 'top_edges', 10 => 't', 11 => 't2sn:', 12 => 'cx:', 13 => 'over:', 14 => 'cx:', 15 => '1', 16 => '-', 17 => 'i:', 18 => 'e', 19 => 'ix:', 20 => ';', 21 => 'top_edges', 22 => ':', 23 => 'left_terms', 24 => 'dup:', 25 => '1', 26 => 'ix:', 27 => '5', 28 => 'pick:', 29 => 'swap:', 30 => 'i:', 31 => 'e', 32 => 'i:', 33 => 'dup:', 34 => '0', 35 => 'i:', 36 => 'subt:', 37 => 'over:', 38 => '1', 39 => 'i:', 40 => 'subt:', 41 => ';', 42 => ' left edges terms', 43 => '.', 44 => 'left_terms', 45 => '3', 46 => 'pick:', 47 => '0', 48 => 'i:', 49 => 'subt:', 50 => '\\*', 51 => '1', 52 => 'pick:', 53 => '4', 54 => 'pick:', 55 => '\\*', 56 => '\\+', 57 => '7', 58 => 'mss:', 59 => 's:', ), 
1 => array ( 0 => array ( 'v' => 'a', ), 1 => array ( 'v' => 'b', ), 
2 => array ( 'v' => '+', 't' => 'oa', 'e' => array ( 0 => 1, 1 => 0, ), ), 
3 => array ( 'v' => 'c', ), 
4 => array ( 'v' => '*', 't' => 'om', 'e' => array ( 0 => 3, 1 => 2, ), ), ), 
2 => 5, 
3 => array ( 'v' => '*', 't' => 'om', 'e' => array ( 0 => 3, 1 => 2, ), ), 
4 => array ( 0 => 3, 1 => 2, ), 
5 => array ( 0 => 3, 1 => 2, ), 
6 => array ( 0 => 1, 1 => 0, ), 
7 => 'b', 
8 => 'a c \\* c b \\* \\+', )
```
