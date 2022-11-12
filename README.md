## Using Environment Variables in Workflows

The environment variables can be used in workflows too just like we use them in our code.

The environment variables can be made available throughout entire workflow or to a specific job.

#### Syntax

```bash
env: 
    <env variable name>: <env variable name>
```
If declared at workflow level, it is available across all jobs.

If declared at job level, it is available across that job only.