<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-pro/s3-secure-cli/blob/master/lib/s3_secure/help/encryption/enable.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

## Example

    $ s3-secure encryption enable a-test-bucket-in-us-east-1
    Encyption enabled on bucket a-test-bucket-in-us-east-1 with rules:
    {:apply_server_side_encryption_by_default=>{:sse_algorithm=>"AES256"}}
    $