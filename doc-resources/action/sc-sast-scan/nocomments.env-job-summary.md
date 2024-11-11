|DO_JOB_SUMMARY<br/>JOB_SUMMARY_ACTION<br/>JOB_SUMMARY_EXTRA_OPTS|If `DO_JOB_SUMMARY` is set to `true` (implied if any of the other two `JOB_SUMMARY_*` variables are set, and implies `DO_WAIT`), a job summary listing scan status and issue counts will be generated using the fcli-provided [SSC `appversion-summary`]({{var:fcli-doc-base-url}}ssc-actions.html#_appversion_summary) or, if specified, the custom fcli action specified through `JOB_SUMMARY_ACTION`. Extra options for the fcli action can be passed through the `JOB_SUMMARY_EXTRA_OPTS` environment variable, for example to allow an unsigned custom action to be used or to specify an SSC filter set. Please see the [SSC Fcli Actions](#ssc-fcli-actions) section below for more details. |