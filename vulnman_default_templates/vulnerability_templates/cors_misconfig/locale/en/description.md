The application implements an HTML5 cross-origin resource sharing (CORS) policy for this request that allows access from any domain.

An HTML5 cross-origin resource sharing (CORS) policy controls whether and how content running on other domains can perform two-way interaction with the domain that publishes the policy.
The policy is fine-grained and can apply access controls per-request based on the URL and other features of the request.
Trusting arbitrary origins effectively disables the same-origin policy, allowing two-way interaction by third-party web sites.
Unless the response consists only of unprotected public content, this policy is likely to present a security risk.
If the site specifies the header *Access-Control-Allow-Credentials: true*, third-party sites may be able to carry out privileged actions and retrieve sensitive information.
Even if it does not, attackers may be able to bypass any IP-based access controls by proxying through users' browsers.
