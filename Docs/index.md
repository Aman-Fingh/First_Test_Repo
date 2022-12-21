### I Design Guide
Foundations
- Separate Concerns
- Require Secure Connections
- Require Versioning in the Accepts Header
Support ETags for Caching
Provide Request-Ids for Introspection
Divide Large Responses Across Requests with Ranges
Requests
Accept serialized JSON in request bodies
Resource names
Actions
Use consistent path formats
Downcase paths and attributes
Support non-id dereferencing for convenience
######Minimize path nesting
Responses
Return appropriate status codes
##Provide full resources where available
Provide resource (UU)IDs
Provide standard timestamps
Provide standard response types
Use UTC times formatted in ISO8601
Nest foreign key relations
Generate structured errors
Show rate limit status
Keep JSON minified in all responses
Artifacts
Provide machine-readable JSON schema
Provide human-readable docs
Provide executable examples
Describe stability
