Tests and Coverage
================
05 September, 2023 19:37:17

- [Coverage](#coverage)
- [Unit Tests](#unit-tests)

This output is created by
[covrpage](https://github.com/yonicd/covrpage).

## Coverage

Coverage summary is created using the
[covr](https://github.com/r-lib/covr) package.

| Object                                              | Coverage (%) |
|:----------------------------------------------------|:------------:|
| FPLDraftEnhancer                                    |    83.78     |
| [R/run_app.R](../R/run_app.R)                       |     0.00     |
| [R/golem_utils_server.R](../R/golem_utils_server.R) |    77.78     |
| [R/golem_utils_ui.R](../R/golem_utils_ui.R)         |    87.94     |
| [R/app_config.R](../R/app_config.R)                 |    100.00    |
| [R/app_ui.R](../R/app_ui.R)                         |    100.00    |

<br>

## Unit Tests

Unit Test summary is created using the
[testthat](https://github.com/r-lib/testthat) package.

| file                                                            |   n | time | error | failed | skipped | warning | icon |
|:----------------------------------------------------------------|----:|-----:|------:|-------:|--------:|--------:|:-----|
| [test-app.R](testthat/test-app.R)                               |   1 | 0.06 |     0 |      0 |       0 |       0 |      |
| [test-fct_helpers.R](testthat/test-fct_helpers.R)               |   1 | 0.01 |     0 |      0 |       0 |       0 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R)   |  10 | 0.12 |     0 |      0 |       1 |       0 | \+   |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R) |  13 | 0.46 |     0 |      0 |       0 |       0 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R)         |  51 | 0.18 |     0 |      0 |       0 |       0 |      |
| [test-utils_helpers.R](testthat/test-utils_helpers.R)           |   1 | 0.00 |     0 |      0 |       0 |       0 |      |

<details open>
<summary>
Show Detailed Test Results
</summary>

| file                                                                    | context            | test                           | status  |   n | time | icon |
|:------------------------------------------------------------------------|:-------------------|:-------------------------------|:--------|----:|-----:|:-----|
| [test-app.R](testthat/test-app.R#L2)                                    | app                | multiplication works           | PASS    |   1 | 0.06 |      |
| [test-fct_helpers.R](testthat/test-fct_helpers.R#L2)                    | fct_helpers        | multiplication works           | PASS    |   1 | 0.01 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R#L3)        | golem-recommended  | app ui                         | PASS    |   2 | 0.08 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R#L13)       | golem-recommended  | app server                     | PASS    |   4 | 0.01 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R#L24_L26)   | golem-recommended  | app_sys works                  | PASS    |   1 | 0.02 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R#L36_L42)   | golem-recommended  | golem-config works             | PASS    |   2 | 0.01 |      |
| [test-golem-recommended.R](testthat/test-golem-recommended.R#L72)       | golem-recommended  | app launches                   | SKIPPED |   1 | 0.00 | \+   |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L2)      | golem_utils_server | not_in works                   | PASS    |   2 | 0.06 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L7)      | golem_utils_server | not_null works                 | PASS    |   2 | 0.02 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L12)     | golem_utils_server | not_na works                   | PASS    |   2 | 0.19 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L17_L22) | golem_utils_server | drop_nulls works               | PASS    |   1 | 0.02 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L26_L29) | golem_utils_server | %\|\|% works                   | PASS    |   2 | 0.01 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L37_L40) | golem_utils_server | %\|NA\|% works                 | PASS    |   2 | 0.02 |      |
| [test-golem_utils_server.R](testthat/test-golem_utils_server.R#L48_L50) | golem_utils_server | rv and rvtl work               | PASS    |   2 | 0.14 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L2)              | golem_utils_ui     | Test with_red_star works       | PASS    |   2 | 0.02 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L10)             | golem_utils_ui     | Test list_to_li works          | PASS    |   3 | 0.01 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L22_L28)         | golem_utils_ui     | Test list_to_p works           | PASS    |   3 | 0.02 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L53)             | golem_utils_ui     | Test named_to_li works         | PASS    |   3 | 0.02 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L66)             | golem_utils_ui     | Test tagRemoveAttributes works | PASS    |   4 | 0.01 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L82)             | golem_utils_ui     | Test undisplay works           | PASS    |   8 | 0.01 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L110)            | golem_utils_ui     | Test display works             | PASS    |   4 | 0.01 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L124)            | golem_utils_ui     | Test jq_hide works             | PASS    |   2 | 0.02 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L132)            | golem_utils_ui     | Test rep_br works              | PASS    |   2 | 0.00 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L140)            | golem_utils_ui     | Test enurl works               | PASS    |   2 | 0.00 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L148)            | golem_utils_ui     | Test columns wrappers works    | PASS    |  16 | 0.05 |      |
| [test-golem_utils_ui.R](testthat/test-golem_utils_ui.R#L172)            | golem_utils_ui     | Test make_action_button works  | PASS    |   2 | 0.01 |      |
| [test-utils_helpers.R](testthat/test-utils_helpers.R#L2)                | utils_helpers      | multiplication works           | PASS    |   1 | 0.00 |      |

| Failed | Warning | Skipped |
|:-------|:--------|:--------|
| !      | \-      | \+      |

</details>
<details>
<summary>
Session Info
</summary>

| Field    | Value                             |
|:---------|:----------------------------------|
| Version  | R version 4.3.1 (2023-06-16 ucrt) |
| Platform | x86_64-w64-mingw32/x64 (64-bit)   |
| Running  | Windows 10 x64 (build 19045)      |
| Language | English_United Kingdom            |
| Timezone | Europe/London                     |

| Package  | Version |
|:---------|:--------|
| testthat | 3.1.9   |
| covr     | 3.6.2   |
| covrpage | 0.2     |

</details>
<!--- Final Status : skipped/warning --->
