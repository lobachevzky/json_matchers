# 0.2.0

* RSpec failure messages include both the body of the response, and the body of
  the JSON Schema file

# 0.1.0

## Breaking Changes

* Remove `schema_for` in favor of using `$ref`. To learn more about `$ref`,
  check out [Understanding JSON Schema Structuring](http://spacetelescope.github.io/understanding-json-schema/structuring.html)

# 0.0.1

## Features

* Validate your Rails response JSON with `match_response_schema`
