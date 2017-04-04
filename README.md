# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

Q-1. What are the 3 parts of a JWT?
Answer
    1. Header
    2. Payload
    3. Signature

Q-2. What information does each part contain?
Answer
    1. Header: The header consist two types of one is JWT and the other is hashing algorithm being used, such as HMAC, SHA256 or RSA.

    2. Payload: Payload contain a claim. Claim is a statement about an entity and additional metadata. Claims consists of reserved, public and private.

    3. Signature: Signature is used to verify that the sender of the JWT and to ensure that message was not changed along way.

Q-3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/.
Answer
    1. As JSON is less verbose than XML, it is smaller in size.
    2. Security-wise JWT uses a public/private key pair in the form of a X.509 certificate for signing.
    3. JSON map directly to the Objects.
    4. JWT is used at Internet scale. This highlights the ease of client-side processing of the JSON Web token on multiple platforms, especially mobile.
