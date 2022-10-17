<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@spruceid/ssx-server](./ssx-server.md) &gt; [SSXServer](./ssx-server.ssxserver.md) &gt; [generateNonce](./ssx-server.ssxserver.generatenonce.md)

## SSXServer.generateNonce property

Generates a nonce for use in the SSX client libraries. Nonce is a random string that is used to prevent replay attacks. Wraps the generateNonce function from the SIWE library.

<b>Signature:</b>

```typescript
generateNonce: () => string;
```