<a name="0.10.0"></a>
# [0.10.0](https://github.com/moooofly/harborctl/compare/v0.9.0...v0.10.0) (2019-01-03)


### Features

* **policy-api:** refactor hierarchy between policy and replication as per [#41](https://github.com/moooofly/harborctl/issues/41) ([8d7177a](https://github.com/moooofly/harborctl/commit/8d7177a))
* **replication-api:** refactor replication related APIs hierarchy ([9415e78](https://github.com/moooofly/harborctl/commit/9415e78))



<a name="0.9.0"></a>
# [0.9.0](https://github.com/moooofly/harborctl/compare/v0.8.0...v0.9.0) (2019-01-03)


* **target-api:** rename cmd name from 'target' to 'registry' ([72103c5](https://github.com/moooofly/harborctl/commit/72103c5))
* **tool:** remove complicated cmd tools out of base release, related to #12 and #5 ([f4f1c25](https://github.com/moooofly/harborctl/commit/f4f1c25))


<a name="0.8.0"></a>
# [0.8.0](https://github.com/moooofly/harborctl/compare/v0.7.0...v0.8.0) (2018-11-12)


### Features

* support user specified target address ([d843dc4](https://github.com/moooofly/harborctl/commit/d843dc4))
* **tool:** add a tool for sync status check ([95de12f](https://github.com/moooofly/harborctl/commit/95de12f))



<a name="0.7.0"></a>
# [0.7.0](https://github.com/moooofly/harborctl/compare/v0.6.0...v0.7.0) (2018-11-08)


### Features

* **policy-api:** add "/policies/replication" APIs ([70fd9aa](https://github.com/moooofly/harborctl/commit/70fd9aa))
* **replication-api:** add "POST /replications" API ([1f81e4b](https://github.com/moooofly/harborctl/commit/1f81e4b))
* **target-api:** add "/targets" APIs ([56d6054](https://github.com/moooofly/harborctl/commit/56d6054))
* **target-api:** add "/targets/ping" and "/targets/{id}/policies" APIs ([c67f2c1](https://github.com/moooofly/harborctl/commit/c67f2c1))



<a name="0.6.0"></a>
# [0.6.0](https://github.com/moooofly/harborctl/compare/v0.5.0...v0.6.0) (2018-11-07)


### Features

* **internal-api:** add "/internal/syncregistry" API ([6ac806e](https://github.com/moooofly/harborctl/commit/6ac806e))
* **job-api:** add "/jobs/replication" APIs ([1a13448](https://github.com/moooofly/harborctl/commit/1a13448))
* **job-api:** add "/jobs/scan/{id}/log" API ([24a9782](https://github.com/moooofly/harborctl/commit/24a9782))
* **systeminfo-api:** add "/systeminfo" APIs ([306cbc5](https://github.com/moooofly/harborctl/commit/306cbc5))



<a name="0.5.0"></a>
# [0.5.0](https://github.com/moooofly/harborctl/compare/v0.4.0...v0.5.0) (2018-11-06)


### Features

* **label-api:** add "/labels/{id}/resources" API ([1937d5a](https://github.com/moooofly/harborctl/commit/1937d5a))
* **label-api:** add list/create/get/update/delete "/labels" APIs ([619406a](https://github.com/moooofly/harborctl/commit/619406a))



<a name="0.4.0"></a>
# [0.4.0](https://github.com/moooofly/harborctl/compare/v0.3.0...v0.4.0) (2018-11-06)


### Features

* **repository-api:** add "/repositories/{repo_name}/tags/{tag}/labels" APIs ([091556f](https://github.com/moooofly/harborctl/commit/091556f))
* **repository-api:** add get/delete/list "/repositories/{repo_name}/tags" APIs ([58113ba](https://github.com/moooofly/harborctl/commit/58113ba))
* **repository-api:** add manifest/retag/scan/vulnerability "/repositories/{repo_name}/tags" APIs ([8fce3b4](https://github.com/moooofly/harborctl/commit/8fce3b4))



<a name="0.3.0"></a>
# [0.3.0](https://github.com/moooofly/harborctl/compare/v0.2.0...v0.3.0) (2018-11-05)


### Features

* **api:** add "/logs" API ([8b89a6e](https://github.com/moooofly/harborctl/commit/8b89a6e))
* **api:** add "/statistics" API ([b821556](https://github.com/moooofly/harborctl/commit/b821556))
* **project-api:** add "HEAD /projects" API ([b2004f6](https://github.com/moooofly/harborctl/commit/b2004f6))
* **repository-api:** add "/repositories/{repo_name}/labels" APIs ([2308a26](https://github.com/moooofly/harborctl/commit/2308a26))
* **repository-api:** add get/delete/update "/repositories" APIs ([f36ef38](https://github.com/moooofly/harborctl/commit/f36ef38))
* **repository-api:** add top/signature/scanAll "/repositories" APIs ([96da1cf](https://github.com/moooofly/harborctl/commit/96da1cf))
* **user-api:** add "/users" APIs ([8f35197](https://github.com/moooofly/harborctl/commit/8f35197))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/moooofly/harborctl/compare/v0.1.0...v0.2.0) (2018-11-02)


### Features

* **project-api:** add "/projects/{project_id}/logs" API ([e3cd578](https://github.com/moooofly/harborctl/commit/e3cd578))
* **project-api:** add "/projects/{project_id}/members" APIs ([564386f](https://github.com/moooofly/harborctl/commit/564386f))
* **project-api:** add metadata related APIs for 'project' ([8d8c69e](https://github.com/moooofly/harborctl/commit/8d8c69e))



<a name="0.1.0"></a>
#  (2018-10-30)


### Features

* **api:** add login/logout APIs, and refactor file hierarchy ([b7f78ae](https://github.com/moooofly/harborctl/commit/b7f78ae))
* **api:** add search API ([e41dd55](https://github.com/moooofly/harborctl/commit/e41dd55))
* **project-api:** add create/delete/get/list/update APIs for 'project' ([96e23b1](https://github.com/moooofly/harborctl/commit/96e23b1))
* refactor: make multiple subcommand files into one ([b7b5188](https://github.com/moooofly/harborctl/commit/b7b5188))



