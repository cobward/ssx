<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@spruceid/ssx-server](./ssx-server.md) &gt; [SSXCookieOptions](./ssx-server.ssxcookieoptions.md)

## SSXCookieOptions interface

Configuration interface for cookies issued by ssx-server

<b>Signature:</b>

```typescript
export interface SSXCookieOptions extends CookieOptions 
```
<b>Extends:</b> CookieOptions

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [httpOnly](./ssx-server.ssxcookieoptions.httponly.md) |  | true | Prevents client-side javascript from accessing cookies. Should always be true. |
|  [sameSite](./ssx-server.ssxcookieoptions.samesite.md) |  | boolean \| 'lax' \| 'strict' \| 'none' \| undefined | Prevents Cross Site Request Forgery Attacks by telling the browser to only send cookies with request from your site. The lax setting allows GET requests from other sites. Recommended true for production. |
|  [secure](./ssx-server.ssxcookieoptions.secure.md) |  | boolean | Whether or not cookies should be sent over https. Recommend true for production. |
|  [signed](./ssx-server.ssxcookieoptions.signed.md) |  | boolean | Whether or not cookies should be signed. Recommended true for production. Set to true by providing a signing key. If false, cookies can be tampered with on the client |
