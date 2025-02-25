#include-components role

The `include-components` role adds components in the DCI jobs from software resources available in the ansible controller node, for example: rpm packages, and git repositories used during the job execution.

Follow this post to know more about [components](https://blog.distributed-ci.io/automate-dci-components.html).

## Configuration

Variables used by this role:

| Setting               | Required | Type   | Description                                                        |
| --------------------- | -------- | ------ | -------------------------------------------------------------------|
| rpms\_to\_components  | True     | List   | List of RPM names to include as components                         |
| gits\_to\_components  | True     | List   | List of directories from GIT repositories to include as components |
