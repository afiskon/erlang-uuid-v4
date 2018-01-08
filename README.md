UUID v4 in pure Erlang
----------------------

Usage:

    1> [ uuid:generate() || I <- lists:seq(1,20) ].
    [<<"78eb3eb1-78ac-46b0-94ca-2eecc14875ae">>,
     <<"8c89cce5-d4d1-45f2-88e0-1afb3288062a">>,
     <<"723adbf5-2702-4109-8d5e-0d604f9619ef">>,
     <<"0b765ec0-cff1-4858-b929-a9931a64f920">>,
     <<"f45b1682-9e6c-4755-b0e4-196039e7c0d2">>,
     <<"06d06111-589d-4c6f-b8af-662b05e9a945">>,
     <<"c305269a-8cac-4261-a389-3a8264cf6989">>,
     <<"2f97c1da-74f7-4880-9a87-ea92765ea9d5">>,
     <<"96f5c8a3-6274-4f01-ac10-ab755f58fc17">>,
     <<"bbf9228c-5d1c-498a-9aa1-6fbd0a66b71b">>,
     <<"e1da5aa8-0e75-4950-9976-853f551a1c02">>,
     <<"bf729d61-f8be-447c-b8ca-0c0d22fdc9a6">>,
     <<"c0e9cc97-4a50-4aab-92e1-97963530111b">>,
     <<"78d925dd-1880-467a-bcea-3b333e00ec97">>,
     <<"540e6e86-1453-4976-af5b-1026850ab18c">>,
     <<"d2c45411-098e-402e-a47e-0bb85b44c909">>,
     <<"a3e604e7-add0-405c-a9a2-6a683e1d8f72">>,
     <<"d0859063-7c23-424b-809c-fa6b29785019">>,
     <<"8af19410-c9e5-41d0-ac82-aaa8e6fd6b2f">>,
     <<"8335ca05-5c63-4850-971e-357e843f2d79">>]

See also: [https://en.wikipedia.org/wiki/UUID][1]


  [1]: https://en.wikipedia.org/wiki/UUID
