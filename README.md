How We implement this
1.  We Encrypt traffic between the customer and your PoP.

WireGuard help us provides an encrypted tunnel. Starlink and other upstreaming service transports the encrypted packets rather than receiving ordinary unencrypted customer DNS and application traffic.

2.  We operate our own DNS resolver.

We use Unbound and support DNS-over-TLS or DNS-over-HTTPS for customers who need encrypted DNS on their devices.

Do not retain individual DNS query histories.

3.  WE NEVER install TLS interception.

WE Do not install a root certificate on customer devices to inspect HTTPS traffic unlike other major isp. We also never not decrypt customer web sessions for analytics.

4.  We separate customer identity from network activity.

Our billing platform is not connected to a database of browsing activity.

5.  We Keep operational telemetry minimal.

We still collect data on weather a customer's connection is online, whether a router is malfunctioning, and how much bandwidth is being used on said router.

We can still collect aggregate bandwidth and device health statistics without keeping you're browsing history and other sensitive data.

6. Established lawful disclosure procedue.

We will have a documented legal-request process. WE DO NOT promise that we will destroy records subject to valid preservation requirements or that we can refuse lawful obligations.


 looking for partner's in network enginnering and serious constructive criticism i want to be clear this is a brand new start up as of 11/21/26
