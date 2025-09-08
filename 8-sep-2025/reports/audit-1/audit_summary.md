# Audit summary

Summary for [Jenkins instance](http://localhost:8080/)

- GitHub Actions Importer version: **1.3.22465 (e880bb33063b12abe98fdc545c7e5f696b4d6758)**
- Performed at: **9/8/25 at 13:41**

## Pipelines

Total: **10**

- Successful: **6 (60%)**
- Partially successful: **2 (20%)**
- Unsupported: **2 (20%)**
- Failed: **0 (0%)**

### Job types

Supported: **8 (80%)**

- flow-definition: **4**
- project: **3**
- org.jenkinsci.plugins.workflow.multibranch.WorkflowMultiBranchProject: **1**

Unsupported: **2 (20%)**

- scripted: **2**

### Build steps

Total: **22**

Known: **19 (86%)**

- echo: **6**
- hudson.tasks.Shell: **4**
- sh: **3**
- junit: **3**
- hudson.plugins.git.GitPublisher: **1**
- checkout: **1**
- archiveArtifacts: **1**

Unknown: **2 (9%)**

- sleep: **2**

Unsupported: **1 (4%)**

- hudson.tasks.Mailer: **1**

Actions: **31**

- run: **14**
- actions/checkout@v4.1.0: **13**
- EnricoMi/publish-unit-test-result-action@v2.12.0: **3**
- actions/upload-artifact@v4.1.0: **1**

### Triggers

Total: **2**

Known: **2 (100%)**

- hudson.triggers.SCMTrigger: **1**
- hudson.triggers.TimerTrigger: **1**

Actions: **8**

- workflow_dispatch: **5**
- schedule: **2**
- push: **1**

### Environment

Total: **6**

Known: **6 (100%)**

- org.jenkinsci.plugins.credentialsbinding.impl.SecretBuildWrapper: **2**
- DB_ENGINE: **2**
- DISABLE_AUTH: **2**

Actions: **6**

- DB_ENGINE: **2**
- DISABLE_AUTH: **2**
- first-var: **1**
- EXPRESSION_VAR: **1**

### Other

Total: **0**

### Manual tasks

Total: **9**

Secrets: **2**

- `${{ secrets.SECRET_TEST_EXPRESSION_VAR }}`: **1**
- `${{ secrets.EXPRESSION_FIRST_VAR }}`: **1**

Self hosted runners: **7**

- `TeamARunner`: **6**
- `DemoRunner`: **1**

### Successful

#### demo_pipeline

- [demo_pipeline/.github/workflows/demo_pipeline.yml](demo_pipeline/.github/workflows/demo_pipeline.yml)
- [demo_pipeline/config.json](demo_pipeline/config.json)
- [demo_pipeline/jenkinsfile](demo_pipeline/jenkinsfile)

#### java_app_gradle_declartive_pl

- [java_app_gradle_declartive_pl/.github/workflows/java_app_gradle_declartive_pl.yml](java_app_gradle_declartive_pl/.github/workflows/java_app_gradle_declartive_pl.yml)
- [java_app_gradle_declartive_pl/config.json](java_app_gradle_declartive_pl/config.json)
- [java_app_gradle_declartive_pl/jenkinsfile](java_app_gradle_declartive_pl/jenkinsfile)

#### java_app_gradle_genric

- [java_app_gradle_genric/.github/workflows/java_app_gradle_genric.yml](java_app_gradle_genric/.github/workflows/java_app_gradle_genric.yml)
- [java_app_gradle_genric/config.json](java_app_gradle_genric/config.json)

#### monas_dev_work/monas_freestyle

- [monas_dev_work/monas_freestyle/.github/workflows/monas_freestyle.yml](monas_dev_work/monas_freestyle/.github/workflows/monas_freestyle.yml)
- [monas_dev_work/monas_freestyle/config.json](monas_dev_work/monas_freestyle/config.json)

#### test_freestyle_project

- [test_freestyle_project/.github/workflows/test_freestyle_project.yml](test_freestyle_project/.github/workflows/test_freestyle_project.yml)
- [test_freestyle_project/config.json](test_freestyle_project/config.json)

#### test_mutlibranch_pipeline

- [test_mutlibranch_pipeline/config.json](test_mutlibranch_pipeline/config.json)

### Partially successful

#### monas_dev_work/monas_pipeline

- [monas_dev_work/monas_pipeline/.github/workflows/monas_pipeline.yml](monas_dev_work/monas_pipeline/.github/workflows/monas_pipeline.yml)
- [monas_dev_work/monas_pipeline/config.json](monas_dev_work/monas_pipeline/config.json)
- [monas_dev_work/monas_pipeline/jenkinsfile](monas_dev_work/monas_pipeline/jenkinsfile)

#### test_pipeline

- [test_pipeline/.github/workflows/test_pipeline.yml](test_pipeline/.github/workflows/test_pipeline.yml)
- [test_pipeline/config.json](test_pipeline/config.json)
- [test_pipeline/jenkinsfile](test_pipeline/jenkinsfile)

### Unsupported

#### groovy_script

- [groovy_script/error.txt](groovy_script/error.txt)
- [groovy_script/config.json](groovy_script/config.json)

#### java_app_gradle_scrippted_pl

- [java_app_gradle_scrippted_pl/error.txt](java_app_gradle_scrippted_pl/error.txt)
- [java_app_gradle_scrippted_pl/config.json](java_app_gradle_scrippted_pl/config.json)

### Failed

#### groovy_script

- [groovy_script/error.txt](groovy_script/error.txt)
- [groovy_script/config.json](groovy_script/config.json)

#### java_app_gradle_scrippted_pl

- [java_app_gradle_scrippted_pl/error.txt](java_app_gradle_scrippted_pl/error.txt)
- [java_app_gradle_scrippted_pl/config.json](java_app_gradle_scrippted_pl/config.json)
