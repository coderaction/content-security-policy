# CONTENT SECURITY POLICY
## _A primary goal of CSP is to mitigate and report XSS attacks_

 XSS attacks exploit the browser’s trust in the content received from the server. Malicious scripts are executed by the victim’s browser because the browser trusts the source of the content, even when it’s not coming from where it seems to be coming from. CSP helps developers to configure the URL of the resources, and if some other resource which is not part of the configuration won’t be loaded into the browser. CSP also helps on mitigating packet sniffing attacks. Content Security Policy can be configured in ASP.NET Core with the help of Content-Security-Policy header.
