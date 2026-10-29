# jwc-call

One static page used by the JWC Desk Gmail add-on. Gmail add-ons can only
open `http(s)` links, so a click-to-call opens
`https://mo-fritz.github.io/jwc-call/#<number>` and this page hands the
number to the computer's phone app (ConnectUC) as a `tel:` link.

Holds no data. The number travels after `#`, which browsers never send to
the server.
