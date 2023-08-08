# Claims And JWT
Authentication is the process of establishing the identity of a user, while authorization determines what actions and resources a user is allowed to access based on their identity.

## Claims-based authorization
involves associating claims with an identity. A claim is a piece of information about the user, such as their name, role, or other attributes. Claims are not about what the user can do, but rather about who the user is. Claims-based authorization checks the value of a claim to determine if a user is granted access to a resource.

An identity can have multiple claims, each with its own value, and multiple claims of the same type.


Standard claims commonly found in JWTs include:

* Issuer (iss): Identifies the principal that issued the JWT.
* Subject (sub): Identifies the subject of the JWT.
* Issued At (iat): Specifies the time at which the JWT was issued.
* JWT ID (jti): A unique identifier for the token, even across different issuers.
