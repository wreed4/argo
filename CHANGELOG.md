# Changelog

## v2.4.3 (2019-12-05)

 * [cfe5f377](https://github.com/argoproj/argo-workflows/commit/cfe5f377bc3552fba90afe6db7a76edd92c753cd) Update version to v2.4.3
 * [256e9a2a](https://github.com/argoproj/argo-workflows/commit/256e9a2abb21f3fc3f3e5434852ff01ffb715a3b) Update version to v2.4.3
 * [b99e6a0e](https://github.com/argoproj/argo-workflows/commit/b99e6a0ea326c0c4616a4ca6a26b8ce22243adb9) Error occurred on pod watch should result in an error on the wait container (#1776)
 * [b00fea14](https://github.com/argoproj/argo-workflows/commit/b00fea143e269f28e0b3a2ba80aef4a1fa4b0ae7) SSL enabled database connection for workflow repository (#1712) (#1756)
 * [400274f4](https://github.com/argoproj/argo-workflows/commit/400274f490ee8407a8cf49f9c5023c0290ecfc4c) Added hint when using certain tokens in when expressions (#1810)
 * [15a0aa7a](https://github.com/argoproj/argo-workflows/commit/15a0aa7a7080bddf00fc6b228d9bf87db194de3b) Handle operation level errors PVC in Retry (#1762)
 * [81c7f5bd](https://github.com/argoproj/argo-workflows/commit/81c7f5bd79e6c792601bcbe9d43acccd9399f5fc) Do not resolve remote templates in lint (#1787)
 * [20cec1d9](https://github.com/argoproj/argo-workflows/commit/20cec1d9bbbae8d9da9a2cd25f74922c940e6d96) Fix retry node name issue on error (#1732)
 * [468cb8fe](https://github.com/argoproj/argo-workflows/commit/468cb8fe52b2208a82e65106a1e5e8cab29d8cac) Refactoring Template Resolution Logic (#1744)
 * [67369fb3](https://github.com/argoproj/argo-workflows/commit/67369fb370fc3adf76dfaee858e3abc5db1a3ceb) Support no-headers flag (#1760)
 * [340ab073](https://github.com/argoproj/argo-workflows/commit/340ab073417df98f2ae698b523e78e1ed0099fce) Filter workflows in list  based on name prefix (#1721)
 * [e9581273](https://github.com/argoproj/argo-workflows/commit/e9581273b5e56066e936ce7f2eb9ccd2652d15cc) Added ability to auto-resume from suspended state (#1715)
 * [a0a1b6fb](https://github.com/argoproj/argo-workflows/commit/a0a1b6fb1b0afbbd19d9815b36a3a32c0126dd4c) Fixed incorrect `pod.name` in retry pods (#1699)

### Contributors

 * Antoine Dao
 * Daisuke Taniwaki
 * Saravanan Balasubramanian
 * Simon Behar
 * gerdos82
 * sang

## v2.4.2 (2019-10-21)

 * [675c6626](https://github.com/argoproj/argo-workflows/commit/675c66267f0c916de0f233d8101aa0646acb46d4) fixed broke metrics endpoint per #1634 (#1695)
 * [1a9310c6](https://github.com/argoproj/argo-workflows/commit/1a9310c6fd089b9f8f848b324cdf219d86684bd4) Apply Strategic merge patch against the pod spec (#1687)
 * [0d0562aa](https://github.com/argoproj/argo-workflows/commit/0d0562aa122b4ef48fd81c3fc2aa9a7bd92ae4ce) Fix retry node processing (#1694)
 * [08f49d01](https://github.com/argoproj/argo-workflows/commit/08f49d01cf6b634f5a2b4e16f4da04bfc51037ab) Print multiple workflows in one command (#1650)
 * [defbc297](https://github.com/argoproj/argo-workflows/commit/defbc297d7e1abb4c729278e362c438cc09d23c7) Added status of previous steps as variables (#1681)
 * [6ac44330](https://github.com/argoproj/argo-workflows/commit/6ac4433020fe48cacfeda60f0f296861e92e742f) Fix issue that workflow.priority substitution didn't pass validation (#1690)
 * [ab9d710a](https://github.com/argoproj/argo-workflows/commit/ab9d710a007eb65f8dc5fddf344d65dca5348ddb) Update version to v2.4.2
 * [338af3e7](https://github.com/argoproj/argo-workflows/commit/338af3e7a4f5b22ef6eead04dffd774baec56391) Store locally referenced template properly (#1670)
 * [be0929dc](https://github.com/argoproj/argo-workflows/commit/be0929dcd89188054a1a3f0ca424d990468d1381) Handle retried node properly (#1669)
 * [88e210de](https://github.com/argoproj/argo-workflows/commit/88e210ded6354f1867837165292901bfb72c2670) Update README.md  Argo Ansible role: Provisioning Argo Workflows on Kubernetes/OpenShift (#1673)
 * [946b0fa2](https://github.com/argoproj/argo-workflows/commit/946b0fa26a11090498b118e69f3f4a840d89afd2) Handle sidecar killing properly (#1675)
 * [4ce972bd](https://github.com/argoproj/argo-workflows/commit/4ce972bd7dba747a0208b5ac1457db4e19390e85) Fix typo (#1679)

### Contributors

 * Daisuke Taniwaki
 * Marek Čermák
 * Rick Avendaño
 * Saravanan Balasubramanian
 * Simon Behar
 * Tobias Bradtke
 * mark9white

## v2.4.1 (2019-10-08)

 * [d7f09999](https://github.com/argoproj/argo-workflows/commit/d7f099992d8cf93c280df2ed38a0b9a1b2614e56) Update version to v2.4.1
 * [6b876b20](https://github.com/argoproj/argo-workflows/commit/6b876b20599e171ff223aaee21e56b39ab978ed7) Don't provision VM for empty artifacts (#1660)
 * [0d00a52e](https://github.com/argoproj/argo-workflows/commit/0d00a52ed28653e3135b3956e62e02efffa62cac) Resolve WorkflowTemplate lazily (#1655)
 * [effd7c33](https://github.com/argoproj/argo-workflows/commit/effd7c33cd73c82ae762cc35b312b180d5ab282e) Stop failing if artifact file exists, but empty (#1653)
 * [a6576314](https://github.com/argoproj/argo-workflows/commit/a65763142ecc2dbd3507f1da860f64220c535f5b) Fix child node template handling (#1654)
 * [982c7c55](https://github.com/argoproj/argo-workflows/commit/982c7c55994c87bab15fd71ef2a17bd905d63edd) Use stored templates to raggregate step outputs (#1651)
 * [a8305ed7](https://github.com/argoproj/argo-workflows/commit/a8305ed7e6f3a4ac5876b1468245716e88e71e92) Fix dag output aggregation correctly (#1649)
 * [f14dd56d](https://github.com/argoproj/argo-workflows/commit/f14dd56d9720ae5116fa6b0e3d320a05fc8bc6f4) Fix DAG output aggregation (#1648)
 * [30c3b937](https://github.com/argoproj/argo-workflows/commit/30c3b937240c0d12eb2ad020d55fe246759a5bbe) Fix missing merged changes in validate.go (#1647)
 * [85f50e30](https://github.com/argoproj/argo-workflows/commit/85f50e30a452a78aab547f17c19fe8464a10685c) fixed example wrong comment (#1643)
 * [09e22fb2](https://github.com/argoproj/argo-workflows/commit/09e22fb257554a33f86bac9dff2532ae23975093) Delay killing sidecars until artifacts are saved (#1645)
 * [99e28f1c](https://github.com/argoproj/argo-workflows/commit/99e28f1ce2baf35d686f04974b878f99e4ca4827) pin colinmarc/hdfs to the next commit, which no longer has vendored deps (#1622)
 * [885aae40](https://github.com/argoproj/argo-workflows/commit/885aae40589dc4f004a0e1027cd651a816e493ee) Fix global lint issue (#1641)
 * [d9c4d236](https://github.com/argoproj/argo-workflows/commit/d9c4d2364dac59750f7f3db3e7e7b48b86ea9694) Merge branch 'release-2.4' of https://github.com/argoproj/argo into release-2.4
 * [972abdd6](https://github.com/argoproj/argo-workflows/commit/972abdd623265777b7ceb6271139812a02471a56) Fix regression where global outputs were unresolveable in DAGs (#1640)
 * [7272bec4](https://github.com/argoproj/argo-workflows/commit/7272bec4655affc5bae7254f1630c5b68948fe15) Fix regression where parallelism could cause workflow to fail (#1639)
 * [6b77abb2](https://github.com/argoproj/argo-workflows/commit/6b77abb2aa40b6c321dd7a6671a2f9ce18e38955) Add back SetGlogLevel calls
 * [e7544f3d](https://github.com/argoproj/argo-workflows/commit/e7544f3d82909b267335b7ee19a4fc6a2f0e5c5b) Update version to v2.4.0
 * [35eae441](https://github.com/argoproj/argo-workflows/commit/35eae4410446098ef379ab84ff73eb5bba4645b0) Merge branch 'master' into release-2.4
 * [45d65889](https://github.com/argoproj/argo-workflows/commit/45d658899be6d2f26eba04a7ce0486280f589c23) Merge branch 'master' into release-2.4
 * [76461f92](https://github.com/argoproj/argo-workflows/commit/76461f925e4e53cdf65b362115d09aa5325dea6b) Update CHANGELOG for v2.4.0 (#1636)
 * [c75a0861](https://github.com/argoproj/argo-workflows/commit/c75a08616e8e6bd1aeb37fc9fc824197491aec9c) Regenerate installation manifests (#1638)
 * [e20cb28c](https://github.com/argoproj/argo-workflows/commit/e20cb28cf8a4f331316535dcfd793ea91c281feb) Grant get secret role to controller to support persistence (#1615)
 * [644946e4](https://github.com/argoproj/argo-workflows/commit/644946e4e07672051f9be0f71ca0d2ca7641648e) Save stored template ID in nodes (#1631)
 * [5d530bec](https://github.com/argoproj/argo-workflows/commit/5d530becae49e1e235d72dd5ac29cc40282bc401) Fix retry workflow state (#1632)
 * [2f0af522](https://github.com/argoproj/argo-workflows/commit/2f0af5221030858e6a5306545ca3577aad17ac1a) Update operator.go (#1630)
 * [6acea0c1](https://github.com/argoproj/argo-workflows/commit/6acea0c1c21a17e14dc95632e80655f7fff09e2e) Store resolved templates (#1552)
 * [df8260d6](https://github.com/argoproj/argo-workflows/commit/df8260d6f64fcacc24c13cf5cc4a3fc3f0a6db18) Increase timeout of golangci-lint (#1623)
 * [138f89f6](https://github.com/argoproj/argo-workflows/commit/138f89f684cec5a8b237584e46199815922f98c3) updated invite link (#1621)
 * [d027188d](https://github.com/argoproj/argo-workflows/commit/d027188d0fce8e44bb0cefb2d46c1e55b9f112a2) Updated the API Rule Violations list (#1618)
 * [a317fbf1](https://github.com/argoproj/argo-workflows/commit/a317fbf1412c4636066def42cd6b7adc732319f3) Prevent controller from crashing due to glog writing to /tmp (#1613)
 * [20e91ea5](https://github.com/argoproj/argo-workflows/commit/20e91ea580e532b9c62f3bd16c5f6f8ed0838fdd) Added WorkflowStatus and NodeStatus types to the Open API Spec. (#1614)
 * [ffb281a5](https://github.com/argoproj/argo-workflows/commit/ffb281a5567666db68a5acab03ba7a0188954bf8) Small code cleanup and add tests (#1562)
 * [1cb8345d](https://github.com/argoproj/argo-workflows/commit/1cb8345de0694cffc30882eac59a05cb8eb06bc4) Add merge keys to Workflow objects to allow for StrategicMergePatches (#1611)
 * [c855a66a](https://github.com/argoproj/argo-workflows/commit/c855a66a6a9e3239fe5d585f5b5f36a07d48c5ed) Increased Lint timeout (#1612)
 * [4bf83fc3](https://github.com/argoproj/argo-workflows/commit/4bf83fc3d0d6b1e1d2c85f7b9b10a051134f7b0a) Fix DAG enable failFast will hang in some case (#1595)
 * [e9f3d9cb](https://github.com/argoproj/argo-workflows/commit/e9f3d9cbc029a9d55cf35ea51c2486078110bb2d) Do not relocate the mounted docker.sock (#1607)
 * [1bd50fa2](https://github.com/argoproj/argo-workflows/commit/1bd50fa2dfd828a04ff012868c98ba33bac41136) Added retry around RuntimeExecutor.Wait call when waiting for main container completion (#1597)
 * [0393427b](https://github.com/argoproj/argo-workflows/commit/0393427b54f397237152f5b74f6d09d0c20c1618) Issue1571  Support ability to assume IAM roles in S3 Artifacts  (#1587)
 * [ffc0c84f](https://github.com/argoproj/argo-workflows/commit/ffc0c84f509226f02d47cb2d5280faa7e2b92841) Update Gopkg.toml and Gopkg.lock (#1596)
 * [aa3a8f1c](https://github.com/argoproj/argo-workflows/commit/aa3a8f1c99fcb70bb199750644f74b17812cc586) Update from github.com/ghodss/yaml to sigs.k8s.io/yaml (#1572)
 * [07a26f16](https://github.com/argoproj/argo-workflows/commit/07a26f16747e3c71e76ba83b43336fd7a49622fb) Regard resource templates as leaf nodes (#1593)
 * [89e959e7](https://github.com/argoproj/argo-workflows/commit/89e959e7aaf396bc09cc012014e425ece2b5d644) Fix workflow template in namespaced controller (#1580)
 * [cd04ab8b](https://github.com/argoproj/argo-workflows/commit/cd04ab8bb923012182f2dc2b35dbf14726f7b1a4) remove redundant codes (#1582)
 * [5bba8449](https://github.com/argoproj/argo-workflows/commit/5bba8449ac7f3c563282eec1cb1f0dfc28d0d7c8) Add entrypoint label to workflow default labels (#1550)
 * [9685d7b6](https://github.com/argoproj/argo-workflows/commit/9685d7b67be91bf81059c1c96120a4fe6288399e) Fix inputs and arguments during template resolution (#1545)
 * [19210ba6](https://github.com/argoproj/argo-workflows/commit/19210ba635a4288f51eb2dd827f03715aea72750) added DataStax as an organization that uses Argo (#1576)
 * [b5f2fdef](https://github.com/argoproj/argo-workflows/commit/b5f2fdef097fe0fd69c60c6ada893547fd944d22) Support AutomountServiceAccountToken and executor specific service account(#1480)
 * [8808726c](https://github.com/argoproj/argo-workflows/commit/8808726cf3d0bc3aa71e3f1653262685dbfa0acf) Fix issue saving outputs which overlap paths with inputs (#1567)
 * [ba7a1ed6](https://github.com/argoproj/argo-workflows/commit/ba7a1ed650e7251dfadf5e9ae1fc2cdda7e9eaa2) Add coverage make target (#1557)
 * [ced0ee96](https://github.com/argoproj/argo-workflows/commit/ced0ee96ced59d9b070a1e81a9c148f78a69bfb9) Document workflow controller dockerSockPath config (#1555)
 * [3e95f2da](https://github.com/argoproj/argo-workflows/commit/3e95f2da6af78cc482009692b65cdc565a0ff412) Optimize argo binary install documentation (#1563)
 * [e2ebb166](https://github.com/argoproj/argo-workflows/commit/e2ebb166683d8a6c96502ce6e72f1a3ae48f0b4b) docs(readme): fix workflow types link (#1560)
 * [6d150a15](https://github.com/argoproj/argo-workflows/commit/6d150a15eb96183fb21faf6a49b0997e6150880b) Initialize the wfClientset before using it (#1548)
 * [5331fc02](https://github.com/argoproj/argo-workflows/commit/5331fc02e257266a4a5887dfe6277e5a0b42e7fc) Remove GLog config from argo executor (#1537)
 * [ed4ac6d0](https://github.com/argoproj/argo-workflows/commit/ed4ac6d0697401da6dec3989ecd63dd7567f0750) Update main.go (#1536)

### Contributors

 * Alexander Matyushentsev
 * Alexey Volkov
 * Anastasia Satonina
 * Anes Benmerzoug
 * Brian Mericle
 * Daisuke Taniwaki
 * David Seapy
 * Ed Lee
 * Erik Parmann
 * Ian Howell
 * Jesse Suen
 * John Wass
 * Jonathon Belotti
 * Mostapha Sadeghipour Roudsari
 * Pablo Osinaga
 * Premkumar Masilamani
 * Saravanan Balasubramanian
 * Simon Behar
 * Takayuki Kasai
 * Xianlu Bird
 * Xie.CS
 * mark9white

## v2.4.0-rc1 (2019-08-08)


### Contributors


## v2.4.0 (2019-10-08)

 * [a6576314](https://github.com/argoproj/argo-workflows/commit/a65763142ecc2dbd3507f1da860f64220c535f5b) Fix child node template handling (#1654)
 * [982c7c55](https://github.com/argoproj/argo-workflows/commit/982c7c55994c87bab15fd71ef2a17bd905d63edd) Use stored templates to raggregate step outputs (#1651)
 * [a8305ed7](https://github.com/argoproj/argo-workflows/commit/a8305ed7e6f3a4ac5876b1468245716e88e71e92) Fix dag output aggregation correctly (#1649)
 * [f14dd56d](https://github.com/argoproj/argo-workflows/commit/f14dd56d9720ae5116fa6b0e3d320a05fc8bc6f4) Fix DAG output aggregation (#1648)
 * [30c3b937](https://github.com/argoproj/argo-workflows/commit/30c3b937240c0d12eb2ad020d55fe246759a5bbe) Fix missing merged changes in validate.go (#1647)
 * [85f50e30](https://github.com/argoproj/argo-workflows/commit/85f50e30a452a78aab547f17c19fe8464a10685c) fixed example wrong comment (#1643)
 * [09e22fb2](https://github.com/argoproj/argo-workflows/commit/09e22fb257554a33f86bac9dff2532ae23975093) Delay killing sidecars until artifacts are saved (#1645)
 * [99e28f1c](https://github.com/argoproj/argo-workflows/commit/99e28f1ce2baf35d686f04974b878f99e4ca4827) pin colinmarc/hdfs to the next commit, which no longer has vendored deps (#1622)
 * [885aae40](https://github.com/argoproj/argo-workflows/commit/885aae40589dc4f004a0e1027cd651a816e493ee) Fix global lint issue (#1641)
 * [d9c4d236](https://github.com/argoproj/argo-workflows/commit/d9c4d2364dac59750f7f3db3e7e7b48b86ea9694) Merge branch 'release-2.4' of https://github.com/argoproj/argo into release-2.4
 * [972abdd6](https://github.com/argoproj/argo-workflows/commit/972abdd623265777b7ceb6271139812a02471a56) Fix regression where global outputs were unresolveable in DAGs (#1640)
 * [7272bec4](https://github.com/argoproj/argo-workflows/commit/7272bec4655affc5bae7254f1630c5b68948fe15) Fix regression where parallelism could cause workflow to fail (#1639)
 * [6b77abb2](https://github.com/argoproj/argo-workflows/commit/6b77abb2aa40b6c321dd7a6671a2f9ce18e38955) Add back SetGlogLevel calls
 * [e7544f3d](https://github.com/argoproj/argo-workflows/commit/e7544f3d82909b267335b7ee19a4fc6a2f0e5c5b) Update version to v2.4.0
 * [35eae441](https://github.com/argoproj/argo-workflows/commit/35eae4410446098ef379ab84ff73eb5bba4645b0) Merge branch 'master' into release-2.4
 * [45d65889](https://github.com/argoproj/argo-workflows/commit/45d658899be6d2f26eba04a7ce0486280f589c23) Merge branch 'master' into release-2.4
 * [76461f92](https://github.com/argoproj/argo-workflows/commit/76461f925e4e53cdf65b362115d09aa5325dea6b) Update CHANGELOG for v2.4.0 (#1636)
 * [c75a0861](https://github.com/argoproj/argo-workflows/commit/c75a08616e8e6bd1aeb37fc9fc824197491aec9c) Regenerate installation manifests (#1638)
 * [e20cb28c](https://github.com/argoproj/argo-workflows/commit/e20cb28cf8a4f331316535dcfd793ea91c281feb) Grant get secret role to controller to support persistence (#1615)
 * [644946e4](https://github.com/argoproj/argo-workflows/commit/644946e4e07672051f9be0f71ca0d2ca7641648e) Save stored template ID in nodes (#1631)
 * [5d530bec](https://github.com/argoproj/argo-workflows/commit/5d530becae49e1e235d72dd5ac29cc40282bc401) Fix retry workflow state (#1632)
 * [2f0af522](https://github.com/argoproj/argo-workflows/commit/2f0af5221030858e6a5306545ca3577aad17ac1a) Update operator.go (#1630)
 * [6acea0c1](https://github.com/argoproj/argo-workflows/commit/6acea0c1c21a17e14dc95632e80655f7fff09e2e) Store resolved templates (#1552)
 * [df8260d6](https://github.com/argoproj/argo-workflows/commit/df8260d6f64fcacc24c13cf5cc4a3fc3f0a6db18) Increase timeout of golangci-lint (#1623)
 * [138f89f6](https://github.com/argoproj/argo-workflows/commit/138f89f684cec5a8b237584e46199815922f98c3) updated invite link (#1621)
 * [d027188d](https://github.com/argoproj/argo-workflows/commit/d027188d0fce8e44bb0cefb2d46c1e55b9f112a2) Updated the API Rule Violations list (#1618)
 * [a317fbf1](https://github.com/argoproj/argo-workflows/commit/a317fbf1412c4636066def42cd6b7adc732319f3) Prevent controller from crashing due to glog writing to /tmp (#1613)
 * [20e91ea5](https://github.com/argoproj/argo-workflows/commit/20e91ea580e532b9c62f3bd16c5f6f8ed0838fdd) Added WorkflowStatus and NodeStatus types to the Open API Spec. (#1614)
 * [ffb281a5](https://github.com/argoproj/argo-workflows/commit/ffb281a5567666db68a5acab03ba7a0188954bf8) Small code cleanup and add tests (#1562)
 * [1cb8345d](https://github.com/argoproj/argo-workflows/commit/1cb8345de0694cffc30882eac59a05cb8eb06bc4) Add merge keys to Workflow objects to allow for StrategicMergePatches (#1611)
 * [c855a66a](https://github.com/argoproj/argo-workflows/commit/c855a66a6a9e3239fe5d585f5b5f36a07d48c5ed) Increased Lint timeout (#1612)
 * [4bf83fc3](https://github.com/argoproj/argo-workflows/commit/4bf83fc3d0d6b1e1d2c85f7b9b10a051134f7b0a) Fix DAG enable failFast will hang in some case (#1595)
 * [e9f3d9cb](https://github.com/argoproj/argo-workflows/commit/e9f3d9cbc029a9d55cf35ea51c2486078110bb2d) Do not relocate the mounted docker.sock (#1607)
 * [1bd50fa2](https://github.com/argoproj/argo-workflows/commit/1bd50fa2dfd828a04ff012868c98ba33bac41136) Added retry around RuntimeExecutor.Wait call when waiting for main container completion (#1597)
 * [0393427b](https://github.com/argoproj/argo-workflows/commit/0393427b54f397237152f5b74f6d09d0c20c1618) Issue1571  Support ability to assume IAM roles in S3 Artifacts  (#1587)
 * [ffc0c84f](https://github.com/argoproj/argo-workflows/commit/ffc0c84f509226f02d47cb2d5280faa7e2b92841) Update Gopkg.toml and Gopkg.lock (#1596)
 * [aa3a8f1c](https://github.com/argoproj/argo-workflows/commit/aa3a8f1c99fcb70bb199750644f74b17812cc586) Update from github.com/ghodss/yaml to sigs.k8s.io/yaml (#1572)
 * [07a26f16](https://github.com/argoproj/argo-workflows/commit/07a26f16747e3c71e76ba83b43336fd7a49622fb) Regard resource templates as leaf nodes (#1593)
 * [89e959e7](https://github.com/argoproj/argo-workflows/commit/89e959e7aaf396bc09cc012014e425ece2b5d644) Fix workflow template in namespaced controller (#1580)
 * [cd04ab8b](https://github.com/argoproj/argo-workflows/commit/cd04ab8bb923012182f2dc2b35dbf14726f7b1a4) remove redundant codes (#1582)
 * [5bba8449](https://github.com/argoproj/argo-workflows/commit/5bba8449ac7f3c563282eec1cb1f0dfc28d0d7c8) Add entrypoint label to workflow default labels (#1550)
 * [9685d7b6](https://github.com/argoproj/argo-workflows/commit/9685d7b67be91bf81059c1c96120a4fe6288399e) Fix inputs and arguments during template resolution (#1545)
 * [19210ba6](https://github.com/argoproj/argo-workflows/commit/19210ba635a4288f51eb2dd827f03715aea72750) added DataStax as an organization that uses Argo (#1576)
 * [b5f2fdef](https://github.com/argoproj/argo-workflows/commit/b5f2fdef097fe0fd69c60c6ada893547fd944d22) Support AutomountServiceAccountToken and executor specific service account(#1480)
 * [8808726c](https://github.com/argoproj/argo-workflows/commit/8808726cf3d0bc3aa71e3f1653262685dbfa0acf) Fix issue saving outputs which overlap paths with inputs (#1567)
 * [ba7a1ed6](https://github.com/argoproj/argo-workflows/commit/ba7a1ed650e7251dfadf5e9ae1fc2cdda7e9eaa2) Add coverage make target (#1557)
 * [ced0ee96](https://github.com/argoproj/argo-workflows/commit/ced0ee96ced59d9b070a1e81a9c148f78a69bfb9) Document workflow controller dockerSockPath config (#1555)
 * [3e95f2da](https://github.com/argoproj/argo-workflows/commit/3e95f2da6af78cc482009692b65cdc565a0ff412) Optimize argo binary install documentation (#1563)
 * [e2ebb166](https://github.com/argoproj/argo-workflows/commit/e2ebb166683d8a6c96502ce6e72f1a3ae48f0b4b) docs(readme): fix workflow types link (#1560)
 * [6d150a15](https://github.com/argoproj/argo-workflows/commit/6d150a15eb96183fb21faf6a49b0997e6150880b) Initialize the wfClientset before using it (#1548)
 * [6131721f](https://github.com/argoproj/argo-workflows/commit/6131721f43545196399d7ffe3a72c1b9dc04df87) Remove GLog config from argo executor (#1537)
 * [5331fc02](https://github.com/argoproj/argo-workflows/commit/5331fc02e257266a4a5887dfe6277e5a0b42e7fc) Remove GLog config from argo executor (#1537)
 * [8e94ca37](https://github.com/argoproj/argo-workflows/commit/8e94ca3709c55dd2004509790e2326d1863de272) Update main.go (#1536)
 * [ed4ac6d0](https://github.com/argoproj/argo-workflows/commit/ed4ac6d0697401da6dec3989ecd63dd7567f0750) Update main.go (#1536)
 * [dfb06b6d](https://github.com/argoproj/argo-workflows/commit/dfb06b6dfa8868324103bb67fbaf712c69238206) Update version to v2.4.0-rc1
 * [9fca1441](https://github.com/argoproj/argo-workflows/commit/9fca144128c97499d11f07a0ee008a9921e1f5f8) Update argo dependencies to kubernetes v1.14 (#1530)
 * [0246d184](https://github.com/argoproj/argo-workflows/commit/0246d184add04e44f77ffbe00e796b3adaf535d2) Use cache to retrieve WorkflowTemplates (#1534)
 * [4864c32f](https://github.com/argoproj/argo-workflows/commit/4864c32ffa40861c5ca066f67615da6d52eaa8b5) Update README.md (#1533)
 * [4df114fa](https://github.com/argoproj/argo-workflows/commit/4df114fae66e87727cfcb871731ec002af1515c7) Update CHANGELOG for v2.4 (#1531)
 * [c7e5cba1](https://github.com/argoproj/argo-workflows/commit/c7e5cba14a835fbfd0aba88b99197675ce1f0c66) Introduce podGC strategy for deleting completed/successful pods (#1234)
 * [bb0d14af](https://github.com/argoproj/argo-workflows/commit/bb0d14af9d320a141cb307b6a883c1eaafa498c3) Update ISSUE_TEMPLATE.md (#1528)
 * [b5702d8a](https://github.com/argoproj/argo-workflows/commit/b5702d8ae725c5caa4058d39f77e6d1e7e549da4) Format sources and order imports with the help of goimports (#1504)
 * [d3ff77bf](https://github.com/argoproj/argo-workflows/commit/d3ff77bf475095c73f034fb3b23c279c62f4269e) Added Architecture doc (#1515)
 * [fc1ec1a5](https://github.com/argoproj/argo-workflows/commit/fc1ec1a51462c9a114417db801e3a9715d3dc6b4) WorkflowTemplate CRD (#1312)
 * [f99d3266](https://github.com/argoproj/argo-workflows/commit/f99d3266d1879579338f124c56f1fc14867308a3) Expose all input parameters to template as JSON (#1488)
 * [bea60526](https://github.com/argoproj/argo-workflows/commit/bea605261be82d8bb91bf703ad68875f1093ebb8) Fix argo logs empty content when workflow run in virtual kubelet env (#1201)
 * [d82de881](https://github.com/argoproj/argo-workflows/commit/d82de8813910afaf9b3fb77d029faa7953bfee3a) Implemented support for WorkflowSpec.ArtifactRepositoryRef (#1350)
 * [0fa20c7b](https://github.com/argoproj/argo-workflows/commit/0fa20c7ba317d8c9a837bcc37d92f3fe79808499) Fix validation (#1508)
 * [87e2cb60](https://github.com/argoproj/argo-workflows/commit/87e2cb6043a305839ca37cc77c7611aaa7bdbd44) Add --dry-run option to `argo submit` (#1506)
 * [e7e50af6](https://github.com/argoproj/argo-workflows/commit/e7e50af6e56b1eeddccc82a2dbc8b421d1a63942) Support git shallow clones and additional ref fetches (#1521)
 * [605489cd](https://github.com/argoproj/argo-workflows/commit/605489cd5dd688527e60efee0aff239e3439c2dc) Allow overriding workflow labels in 'argo submit' (#1475)
 * [47eba519](https://github.com/argoproj/argo-workflows/commit/47eba519107c229edf61dbe024a6a5e0f1618a8d) Fix issue [Documentation] kubectl get service argo-artifacts -o wide (#1516)
 * [02f38262](https://github.com/argoproj/argo-workflows/commit/02f38262c40901346ddd622685bc6bfd344a2717) Fixed #1287 Executor kubectl version is obsolete (#1513)
 * [f62105e6](https://github.com/argoproj/argo-workflows/commit/f62105e659a22ccc0875151698eab540090885f6) Allow Makefile variables to be set from the command line (#1501)
 * [e62be65b](https://github.com/argoproj/argo-workflows/commit/e62be65ba25ae68a1bed10bddf33b4dae4991249) Fix a compiler error in a unit test (#1514)
 * [5c5c29af](https://github.com/argoproj/argo-workflows/commit/5c5c29af729b39f5f9b8a7fe6b8c1dede53eae3a) Fix the lint target (#1505)
 * [e03287bf](https://github.com/argoproj/argo-workflows/commit/e03287bfb7f97f639c8d81617808f709ca547eaa) Allow output parameters with .value, not only .valueFrom (#1336)
 * [781d3b8a](https://github.com/argoproj/argo-workflows/commit/781d3b8ae243b2c32ea3c4abd5b4a99fe9fc9cad) Implemented Conditionally annotate outputs of script template only when consumed #1359 (#1462)
 * [b028e61d](https://github.com/argoproj/argo-workflows/commit/b028e61db71e74b5730469a5f23a734937ddb8d9) change 'continue-on-fail' example to better reflect its description (#1494)
 * [97e824c9](https://github.com/argoproj/argo-workflows/commit/97e824c9a5b71baea658e8de6130bee089fb764d) Readme update to add argo and airflow comparison (#1502)
 * [414d6ce7](https://github.com/argoproj/argo-workflows/commit/414d6ce7b8aebcbd3b8822f407ec71ed465c103d) Fix a compiler error (#1500)
 * [ca1d5e67](https://github.com/argoproj/argo-workflows/commit/ca1d5e671519aaa9f38f5f2564eb70c138fadda7) Fix: Support the List within List type in withParam #1471 (#1473)
 * [75cb8b9c](https://github.com/argoproj/argo-workflows/commit/75cb8b9cd92cd7fcce4b921b88232bb05f2672b2) Fix #1366 unpredictable global artifact behavior (#1461)
 * [082e5c4f](https://github.com/argoproj/argo-workflows/commit/082e5c4f617c4120584ad601a8d85e0a3ce36a26) Exposed workflow priority as a variable (#1476)
 * [38c4def7](https://github.com/argoproj/argo-workflows/commit/38c4def7fb100e954757649553db8c04ea64f318) Fix: Argo CLI should show warning if there is no workflow definition in file #1486
 * [af7e496d](https://github.com/argoproj/argo-workflows/commit/af7e496db6ee8c10c9a2b6b51a27265bc6b0ee6d) Add Commodus Tech as official user (#1484)
 * [8c559642](https://github.com/argoproj/argo-workflows/commit/8c559642f2ec8abaea3204279fa3d6ff5ad40add) Update OWNERS (#1485)
 * [007d1f88](https://github.com/argoproj/argo-workflows/commit/007d1f8816736a758fa3720f0081e01dbc4200e3) Fix: 1008 `argo wait` and `argo submit --wait` should exit 1 if workflow fails  (#1467)
 * [3ab7bc94](https://github.com/argoproj/argo-workflows/commit/3ab7bc94c01d7a470bd05198b99c33e1a0221847) Document the insecureIgnoreHostKey git flag (#1483)
 * [7d9bb51a](https://github.com/argoproj/argo-workflows/commit/7d9bb51ae328f1a8cc7daf7d8ef108cf190df0ce) Fix failFast bug:   When a node in the middle fails, the entire workflow will hang (#1468)
 * [42adbf32](https://github.com/argoproj/argo-workflows/commit/42adbf32e8d4c626c544795c2fc1adb70676e968) Add --no-color flag to logs (#1479)
 * [67fc29c5](https://github.com/argoproj/argo-workflows/commit/67fc29c57db795a7020f355ab32cd883cfaf701e) fix typo: symboloic > symbolic (#1478)
 * [7c3e1901](https://github.com/argoproj/argo-workflows/commit/7c3e1901f49fe34cbe9d084274f6e64c48270635) Added Codec to the Argo community list (#1477)
 * [0a9cf9d3](https://github.com/argoproj/argo-workflows/commit/0a9cf9d3b06a3b304c0c690a298d8dc3d51c015b) Add doc about failFast feature (#1453)
 * [6a590300](https://github.com/argoproj/argo-workflows/commit/6a5903000fe8a7b3610c32435b2363cbf6334d1b) Support PodSecurityContext (#1463)
 * [e392d854](https://github.com/argoproj/argo-workflows/commit/e392d854bf78db89413782a23e62b0e38cf9c780) issue-1445: changing temp directory for output artifacts from root to tmp (#1458)
 * [7a21adfe](https://github.com/argoproj/argo-workflows/commit/7a21adfeb0af18c2452648a8bb3698a687f99b5e) New Feature:  provide failFast flag, allow a DAG to run all branches of the DAG (either success or failure) (#1443)
 * [b9b87b7f](https://github.com/argoproj/argo-workflows/commit/b9b87b7fa0cd3177c2b89cacff189f4893c5af95) Centralized Longterm workflow persistence storage  (#1344)
 * [cb09609b](https://github.com/argoproj/argo-workflows/commit/cb09609bd646a394c3a6f739dd447022a2bdb327) mention sidecar in failure message for sidecar containers (#1430)
 * [373bbe6e](https://github.com/argoproj/argo-workflows/commit/373bbe6ec9e819c39152292f79752792ce40b94d) Fix demo's doc issue of install minio chart (#1450)
 * [83552334](https://github.com/argoproj/argo-workflows/commit/835523341bcc96b6e9358be71e7432d0ac4058c5) Add threekit to user list (#1444)
 * [83f82ad1](https://github.com/argoproj/argo-workflows/commit/83f82ad172de0472643495d3ef3e0ce6d959900a) Improve bash completion (#1437)
 * [ee0ec78a](https://github.com/argoproj/argo-workflows/commit/ee0ec78ac98eaa112d343906a6e9b6490c39817f) Update documentation for workflow.outputs.artifacts (#1439)
 * [9e30c06e](https://github.com/argoproj/argo-workflows/commit/9e30c06e32b072b87e0d17095448d114175c713f) Revert "Update demo.md (#1396)" (#1433)
 * [c08de630](https://github.com/argoproj/argo-workflows/commit/c08de6300c3b394c34a5b3596455dcb50c29af48) Add paging function for list command (#1420)
 * [bba2f9cb](https://github.com/argoproj/argo-workflows/commit/bba2f9cbe9aa0eb053c19b03bc8fa7c002f579b0) Fixed:  Implemented Template level service account (#1354)
 * [d635c1de](https://github.com/argoproj/argo-workflows/commit/d635c1def74936869edbd8b9037ac81ea0af1772) Ability to configure hostPath mount for `/var/run/docker.sock` (#1419)
 * [d2f7162a](https://github.com/argoproj/argo-workflows/commit/d2f7162ac26550642ebe1792c65fb5e6ca9c0e7a) Terminate all containers within pod after main container completes (#1423)
 * [1607d74a](https://github.com/argoproj/argo-workflows/commit/1607d74a8de0704b82627364645a99b699d40cc0) PNS executor intermitently failed to capture entire log of script templates (#1406)
 * [5e47256c](https://github.com/argoproj/argo-workflows/commit/5e47256c7f86b56cfbf2ce53f73ed093eef2e3b6) Fix typo (#1431)
 * [5635c33a](https://github.com/argoproj/argo-workflows/commit/5635c33aa263080fe84e29a11a52f86fee583ca2) Update demo.md (#1396)
 * [83425455](https://github.com/argoproj/argo-workflows/commit/83425455bff34527e65ca1371347eed5203ae99a) Add OVH as official user (#1417)
 * [82e5f63d](https://github.com/argoproj/argo-workflows/commit/82e5f63d3680e7e4a22747803b0753b5ec31d2ad) Typo fix in ARTIFACT_REPO.md (#1425)
 * [15fa6f52](https://github.com/argoproj/argo-workflows/commit/15fa6f52d926ee5e839321900f613f6e546e6b6e) Update OWNERS (#1429)
 * [96b9a40e](https://github.com/argoproj/argo-workflows/commit/96b9a40e9aafe9c0132ce1b9f1eb01f05c3894ca) Orders uses alphabetically (#1411)
 * [6550e2cb](https://github.com/argoproj/argo-workflows/commit/6550e2cb10112ddf6435755958387ffa6ada0ef5) chore: add IBM to official users section in README.md (#1409)
 * [bc81fe28](https://github.com/argoproj/argo-workflows/commit/bc81fe288ebf9811774b36dd6eba9a851ac7717e) Fiixed: persistentvolumeclaims already exists #1130 (#1363)
 * [6a042d1f](https://github.com/argoproj/argo-workflows/commit/6a042d1f7eb01f1f369c2325aecebf71a3bea3a4) Update README.md (#1404)
 * [aa811fbd](https://github.com/argoproj/argo-workflows/commit/aa811fbdb914fe386cfbf3fa84a51bfd5104b5d0) Update README.md (#1402)
 * [abe3c99f](https://github.com/argoproj/argo-workflows/commit/abe3c99f19a1ec28775a276b50ad588a2dd660ca) Add Mirantis as an official user (#1401)
 * [18ab750a](https://github.com/argoproj/argo-workflows/commit/18ab750aea4de8f7dc67433f4e73505c80e13222) Added Argo Rollouts to README (#1388)
 * [67714f99](https://github.com/argoproj/argo-workflows/commit/67714f99b4bf664eb5e853b25ebf4b12bb98f733) Make locating kubeconfig in example os independent (#1393)
 * [672dc04f](https://github.com/argoproj/argo-workflows/commit/672dc04f737a3be099fe64c343587c35074b0938) Fixed: withParam parsing of JSON/YAML lists #1389 (#1397)
 * [b9aec5f9](https://github.com/argoproj/argo-workflows/commit/b9aec5f9833d5fa2055d06d1a71fdb75709eea21) Fixed: make verify-codegen is failing on the master branch (#1399) (#1400)
 * [270aabf1](https://github.com/argoproj/argo-workflows/commit/270aabf1d8cabd69b9851209ad5d9c874348e21d) Fixed:  failed to save outputs: verify serviceaccount default:default has necessary privileges (#1362)
 * [163f4a5d](https://github.com/argoproj/argo-workflows/commit/163f4a5d322352bd98f9a88ebd6089cf5e5b49ad) Fixed: Support hostAliases in WorkflowSpec #1265 (#1365)
 * [abb17478](https://github.com/argoproj/argo-workflows/commit/abb174788dce1bc6bed993a2967f7d8e112e44ca) Add Max Kelsen to USERS in README.md (#1374)
 * [dc549193](https://github.com/argoproj/argo-workflows/commit/dc5491930e09eebe700952e28359deeb8e0d2314) Update docs for the v2.3.0 release and to use the stable tag
 * [4001c964](https://github.com/argoproj/argo-workflows/commit/4001c964dbc70962e1cc1d80a4aff64cf8594ec3) Update README.md (#1372)
 * [6c18039b](https://github.com/argoproj/argo-workflows/commit/6c18039be962996d971145be8349d2ed3e396c80) Fix issue where a DAG with exhausted retries would get stuck Running (#1364)
 * [d7e74fe3](https://github.com/argoproj/argo-workflows/commit/d7e74fe3a96277ba532e4a2f40303a92d2d0ce94) Validate action for resource templates (#1346)
 * [810949d5](https://github.com/argoproj/argo-workflows/commit/810949d5106b4d1d533b647d1d61559c208b590a) Fixed :  CLI Does Not Honor metadata.namespace #1288 (#1352)
 * [e58859d7](https://github.com/argoproj/argo-workflows/commit/e58859d79516508838fead8222f0e26a6c2a2861) [Fix #1242] Failed DAG nodes are now kept and set to running on RetryWorkflow. (#1250)
 * [d5fe5f98](https://github.com/argoproj/argo-workflows/commit/d5fe5f981fb112ba01ed77521ae688f8a15f67b9) Use golangci-lint instead of deprecated gometalinter (#1335)
 * [26744d10](https://github.com/argoproj/argo-workflows/commit/26744d100e91eb757f48bfedd539e7e4a044faf3) Support an easy way to set owner reference (#1333)
 * [8bf7578e](https://github.com/argoproj/argo-workflows/commit/8bf7578e1884c61128603bbfaa677fd79cc17ea8) Add --status filter for get command (#1325)
 * [3f6ac9c9](https://github.com/argoproj/argo-workflows/commit/3f6ac9c9f1ccd92d4dabf52e964a1dd52b1622f6) Update release instructions

### Contributors

 * Aisuko
 * Alex Capras
 * Alex Collins
 * Alexander Matyushentsev
 * Alexey Volkov
 * Anastasia Satonina
 * Anes Benmerzoug
 * Ben Wells
 * Brandon Steinman
 * Brian Mericle
 * Christian Muehlhaeuser
 * Cristian Pop
 * Daisuke Taniwaki
 * Daniel Duvall
 * David Seapy
 * Ed Lee
 * Edwin Jacques
 * Erik Parmann
 * Ian Howell
 * Jacob O'Farrell
 * Jaime
 * Jean-Louis Queguiner
 * Jesse Suen
 * John Wass
 * Jonathon Belotti
 * Mostapha Sadeghipour Roudsari
 * Mukulikak
 * Orion Delwaterman
 * Pablo Osinaga
 * Paul Brit
 * Premkumar Masilamani
 * Saravanan Balasubramanian
 * Semjon Kopp
 * Stephen Steiner
 * Takayuki Kasai
 * Tim Schrodi
 * Xianlu Bird
 * Xie.CS
 * Ziyang Wang
 * alex weidner
 * commodus-sebastien
 * hidekuro
 * ianCambrio
 * jacky
 * mark9white
 * tralexa

## v2.3.0-rc3 (2019-05-07)

 * [2274130d](https://github.com/argoproj/argo-workflows/commit/2274130dc55de0b019ac9fd5232c192364f275c9) Update version to v2.3.0-rc3
 * [b024b3d8](https://github.com/argoproj/argo-workflows/commit/b024b3d83a4bfd46bd6b4a5075e9f8f968457309) Fix: # 1328 argo submit --wait and argo wait quits while workflow is running (#1347)
 * [24680b7f](https://github.com/argoproj/argo-workflows/commit/24680b7fc8a1fd573b39d61ba7bdce5b143eb686) Fixed : Validate the secret credentials name and key (#1358)
 * [f641d84e](https://github.com/argoproj/argo-workflows/commit/f641d84eb5cd489c98b39b41b69dbea9a3312e01) Fix input artifacts with multiple ssh keys (#1338)
 * [e680bd21](https://github.com/argoproj/argo-workflows/commit/e680bd219a2478835d5d8cefcbfb96bd11acc40b) add / test (#1240)
 * [ee788a8a](https://github.com/argoproj/argo-workflows/commit/ee788a8a6c70c5c64f535b6a901e837a9b4d5797) Fix #1340 parameter substitution bug (#1345)
 * [60b65190](https://github.com/argoproj/argo-workflows/commit/60b65190a22e176429e586afe58a86a14b390c66) Fix missing template local volumes, Handle volumes only used in init containers (#1342)
 * [4e37a444](https://github.com/argoproj/argo-workflows/commit/4e37a444bde2a034885d0db35f7b38684505063e) Add documentation on releasing

### Contributors

 * Daisuke Taniwaki
 * Hideto Inamura
 * Ilias Katsakioris
 * Jesse Suen
 * Saravanan Balasubramanian
 * almariah

## v2.3.0-rc2 (2019-04-21)

 * [bb1bfdd9](https://github.com/argoproj/argo-workflows/commit/bb1bfdd9106d9b64aa2dccf8d3554bdd31513cf8) Update version to v2.3.0-rc2. Update changelog
 * [49a6b6d7](https://github.com/argoproj/argo-workflows/commit/49a6b6d7ac1bb5f6b390eff1b218205d995142cb) wait will conditionally become privileged if main/sidecar privileged (resolves #1323)
 * [34af5a06](https://github.com/argoproj/argo-workflows/commit/34af5a065e42230148b48603fc81f57fb2b4c22c) Fix regression where argoexec wait would not return when podname was too long
 * [bd8d5cb4](https://github.com/argoproj/argo-workflows/commit/bd8d5cb4b7510afb7bd43bd75e5c5d26ccc85ca4) `argo list` was not displaying non-zero priorities correctly
 * [64370a2d](https://github.com/argoproj/argo-workflows/commit/64370a2d185db66a8d2188d986c52a3b73aaf92b) Support parameter substitution in the volumes attribute (#1238)
 * [6607dca9](https://github.com/argoproj/argo-workflows/commit/6607dca93db6255a2abc30ae76b5f935fce5735d) Issue1316 Pod creation with secret volumemount  (#1318)
 * [a5a2bcf2](https://github.com/argoproj/argo-workflows/commit/a5a2bcf21900019d979328250009af4137f7ff2a) Update README.md (#1321)
 * [950de1b9](https://github.com/argoproj/argo-workflows/commit/950de1b94efc18473a85e1f23c9ed5e6ff75ba93) Export the methods of `KubernetesClientInterface` (#1294)
 * [1c729a72](https://github.com/argoproj/argo-workflows/commit/1c729a72a2ae431623332b65646c97cb689eab01) Update v2.3.0 CHANGELOG.md

### Contributors

 * Chris Chambers
 * Ed Lee
 * Ilias Katsakioris
 * Jesse Suen
 * Saravanan Balasubramanian

## v2.3.0-rc1 (2019-04-10)


### Contributors


## v2.3.0 (2019-05-20)

 * [88fcc70d](https://github.com/argoproj/argo-workflows/commit/88fcc70dcf6e60697e6716edc7464a403c49b27e) Update VERSION to v2.3.0, changelog, and manifests
 * [1731cd7c](https://github.com/argoproj/argo-workflows/commit/1731cd7c2cd6a739d9efb369a7732bc15498460f) Fix issue where a DAG with exhausted retries would get stuck Running (#1364)
 * [3f6ac9c9](https://github.com/argoproj/argo-workflows/commit/3f6ac9c9f1ccd92d4dabf52e964a1dd52b1622f6) Update release instructions
 * [2274130d](https://github.com/argoproj/argo-workflows/commit/2274130dc55de0b019ac9fd5232c192364f275c9) Update version to v2.3.0-rc3
 * [b024b3d8](https://github.com/argoproj/argo-workflows/commit/b024b3d83a4bfd46bd6b4a5075e9f8f968457309) Fix: # 1328 argo submit --wait and argo wait quits while workflow is running (#1347)
 * [24680b7f](https://github.com/argoproj/argo-workflows/commit/24680b7fc8a1fd573b39d61ba7bdce5b143eb686) Fixed : Validate the secret credentials name and key (#1358)
 * [f641d84e](https://github.com/argoproj/argo-workflows/commit/f641d84eb5cd489c98b39b41b69dbea9a3312e01) Fix input artifacts with multiple ssh keys (#1338)
 * [e680bd21](https://github.com/argoproj/argo-workflows/commit/e680bd219a2478835d5d8cefcbfb96bd11acc40b) add / test (#1240)
 * [ee788a8a](https://github.com/argoproj/argo-workflows/commit/ee788a8a6c70c5c64f535b6a901e837a9b4d5797) Fix #1340 parameter substitution bug (#1345)
 * [60b65190](https://github.com/argoproj/argo-workflows/commit/60b65190a22e176429e586afe58a86a14b390c66) Fix missing template local volumes, Handle volumes only used in init containers (#1342)
 * [4e37a444](https://github.com/argoproj/argo-workflows/commit/4e37a444bde2a034885d0db35f7b38684505063e) Add documentation on releasing
 * [bb1bfdd9](https://github.com/argoproj/argo-workflows/commit/bb1bfdd9106d9b64aa2dccf8d3554bdd31513cf8) Update version to v2.3.0-rc2. Update changelog
 * [49a6b6d7](https://github.com/argoproj/argo-workflows/commit/49a6b6d7ac1bb5f6b390eff1b218205d995142cb) wait will conditionally become privileged if main/sidecar privileged (resolves #1323)
 * [34af5a06](https://github.com/argoproj/argo-workflows/commit/34af5a065e42230148b48603fc81f57fb2b4c22c) Fix regression where argoexec wait would not return when podname was too long
 * [bd8d5cb4](https://github.com/argoproj/argo-workflows/commit/bd8d5cb4b7510afb7bd43bd75e5c5d26ccc85ca4) `argo list` was not displaying non-zero priorities correctly
 * [64370a2d](https://github.com/argoproj/argo-workflows/commit/64370a2d185db66a8d2188d986c52a3b73aaf92b) Support parameter substitution in the volumes attribute (#1238)
 * [6607dca9](https://github.com/argoproj/argo-workflows/commit/6607dca93db6255a2abc30ae76b5f935fce5735d) Issue1316 Pod creation with secret volumemount  (#1318)
 * [a5a2bcf2](https://github.com/argoproj/argo-workflows/commit/a5a2bcf21900019d979328250009af4137f7ff2a) Update README.md (#1321)
 * [950de1b9](https://github.com/argoproj/argo-workflows/commit/950de1b94efc18473a85e1f23c9ed5e6ff75ba93) Export the methods of `KubernetesClientInterface` (#1294)
 * [1c729a72](https://github.com/argoproj/argo-workflows/commit/1c729a72a2ae431623332b65646c97cb689eab01) Update v2.3.0 CHANGELOG.md
 * [40f9a875](https://github.com/argoproj/argo-workflows/commit/40f9a87593d312a46f7fa24aaf32e125458cc701) Reorganize manifests to kustomize 2 and update version to v2.3.0-rc1
 * [75b28a37](https://github.com/argoproj/argo-workflows/commit/75b28a37b923e278fc89fd647f78a42e7a3bf029) Implement support for PNS (Process Namespace Sharing) executor (#1214)
 * [b4edfd30](https://github.com/argoproj/argo-workflows/commit/b4edfd30b0e3034d98e938b491cf5bd054b36525) Fix SIGSEGV in watch/CheckAndDecompress. Consolidate duplicate code (resolves #1315)
 * [02550be3](https://github.com/argoproj/argo-workflows/commit/02550be31e53da79f1f4dbebda3ede7dc1052086) Archive location should conditionally be added to template only when needed
 * [c60010da](https://github.com/argoproj/argo-workflows/commit/c60010da29bd36c10c6e627802df6d6a06c1a59a) Fix nil pointer dereference with secret volumes (#1314)
 * [db89c477](https://github.com/argoproj/argo-workflows/commit/db89c477d65a29fc0a95ca55f68e1bd23d0170e0) Fix formatting issues in examples documentation (#1310)
 * [0d400f2c](https://github.com/argoproj/argo-workflows/commit/0d400f2ce6db9478b4eaa6fe24849a686c9d1d44) Refactor checkandEstimate to optimize podReconciliation (#1311)
 * [bbdf2e2c](https://github.com/argoproj/argo-workflows/commit/bbdf2e2c8f1b5a8dc83e88fedba9b1899f6bc78b) Add alibaba cloud to officially using argo list (#1313)
 * [abb77062](https://github.com/argoproj/argo-workflows/commit/abb77062fc06ae964ce7ccd1a534ec8bbdf3747c) CheckandEstimate implementation to optimize podReconciliation (#1308)
 * [1a028d54](https://github.com/argoproj/argo-workflows/commit/1a028d5458ffef240f8af31caeecda91f057c3ba) Secrets should be passed to pods using volumes instead of API calls (#1302)
 * [e34024a3](https://github.com/argoproj/argo-workflows/commit/e34024a3ca285d1af3b5ba3b3235dc7adc0472b7) Add support for init containers (#1183)
 * [4591e44f](https://github.com/argoproj/argo-workflows/commit/4591e44fe0e4de543f4c4339de0808346e0807e3) Added support for artifact path references (#1300)
 * [928e4df8](https://github.com/argoproj/argo-workflows/commit/928e4df81c4b33f0c0750f01b3aa3c4fc7ff256c) Add Karius to users in README.md (#1305)
 * [de779f36](https://github.com/argoproj/argo-workflows/commit/de779f36122205790915622f5ee91c9a9d5b9086) Add community meeting notes link (#1304)
 * [a8a55579](https://github.com/argoproj/argo-workflows/commit/a8a55579131605d4dc769cb599bc99c06350dfb7) Speed up podReconciliation using parallel goroutine (#1286)
 * [93451119](https://github.com/argoproj/argo-workflows/commit/934511192e4045b87be1675ff7e9dfa79faa9fcb) Add dns config support (#1301)
 * [850f3f15](https://github.com/argoproj/argo-workflows/commit/850f3f15dd1965e99cd636711a5e3306bc4bd0c0) Admiralty: add link to blog post, add user (#1295)
 * [d5f4b428](https://github.com/argoproj/argo-workflows/commit/d5f4b428ce02de34a37d5cb2fdba4dfa9fd16e75) Fix for Resource creation where template has same parameter templating (#1283)
 * [9b555cdb](https://github.com/argoproj/argo-workflows/commit/9b555cdb30f6092d5f53891f318fb74b8371c039) Issue#896 Workflow steps with non-existant output artifact path will succeed (#1277)
 * [adab9ed6](https://github.com/argoproj/argo-workflows/commit/adab9ed6bc4f8f337105182c56abad39bccb9676) Argo CI is current inactive (#1285)
 * [59fcc5cc](https://github.com/argoproj/argo-workflows/commit/59fcc5cc33ce67c057064dc37a463707501615e1) Add workflow labels and annotations global vars (#1280)
 * [1e111caa](https://github.com/argoproj/argo-workflows/commit/1e111caa1d2cc672b3b53c202b96a5f660a7e9b2) Fix bug with DockerExecutor's CopyFile (#1275)
 * [73a37f2b](https://github.com/argoproj/argo-workflows/commit/73a37f2b2a12d74ddf6a4b54e04b50fa1a7c68a1) Add the `mergeStrategy` option to resource patching (#1269)
 * [e6105243](https://github.com/argoproj/argo-workflows/commit/e6105243c785d9f53aef6fcfd344e855ad4f7d84) Reduce redundancy pod label action (#1271)
 * [4bfbb20b](https://github.com/argoproj/argo-workflows/commit/4bfbb20bc23f8bf4611a6314fb80f8138b17b9b9) Error running 1000s of tasks: "etcdserver: request is too large" #1186 (#1264)
 * [b2743f30](https://github.com/argoproj/argo-workflows/commit/b2743f30c411f5ad8f8c8b481a5d6b6ff83c33bd) Proxy Priority and PriorityClassName to pods (#1179)
 * [70c130ae](https://github.com/argoproj/argo-workflows/commit/70c130ae626f7c58d9e5ac0eed8977f51696fcbd) Update versions (#1218)
 * [b0384129](https://github.com/argoproj/argo-workflows/commit/b03841297e4b0dab0380b441cf41f5ed34db44bf) Git cloning via SSH was not verifying host public key (#1261)
 * [3f06385b](https://github.com/argoproj/argo-workflows/commit/3f06385b129c02e23ea283f7c66d347cb8899564) Issue#1165 fake outputs don't notify and task completes successfully (#1247)
 * [fa042aa2](https://github.com/argoproj/argo-workflows/commit/fa042aa285947c5fa365ef06a9565d0b4e20da0e) typo, executo -> executor (#1243)
 * [1cb88bae](https://github.com/argoproj/argo-workflows/commit/1cb88baee9ded1ede27a9d3f1e31f06f4369443d) Fixed Issue#1223 Kubernetes Resource action: patch is not supported (#1245)
 * [2b0b8f1c](https://github.com/argoproj/argo-workflows/commit/2b0b8f1c3f46aa41e4b4ddaf14ad1fdebccfaf8a) Fix the Prometheus address references (#1237)
 * [94cda3d5](https://github.com/argoproj/argo-workflows/commit/94cda3d53c6a72e3fc225ba08796bfd9420eccd6) Add feature to continue workflow on failed/error steps/tasks (#1205)
 * [3f1fb9d5](https://github.com/argoproj/argo-workflows/commit/3f1fb9d5e61d300c4922e48a748dc17285e07f07) Add Gardener to "Who uses Argo" (#1228)
 * [cde5cd32](https://github.com/argoproj/argo-workflows/commit/cde5cd320fa987ac6dd539a3126f29c73cd7277a) Include stderr when retrieving docker logs (#1225)
 * [2b1d56e7](https://github.com/argoproj/argo-workflows/commit/2b1d56e7d4e583e2e06b37904714b350faf03d97) Update README.md (#1224)
 * [eeac5a0e](https://github.com/argoproj/argo-workflows/commit/eeac5a0e11b4a6f4bc28757a3b0684598b8c4974) Remove extra quotes around output parameter value (#1232)
 * [8b67e1bf](https://github.com/argoproj/argo-workflows/commit/8b67e1bfdc7ed5ea153cb17f9a740afe2bd4efa8) Update README.md (#1236)
 * [baa3e622](https://github.com/argoproj/argo-workflows/commit/baa3e622121e66c9fec7c612c88027b7cacbd1b2) Update README with typo fixes (#1220)
 * [f6b0c8f2](https://github.com/argoproj/argo-workflows/commit/f6b0c8f285217fd0e6089b0cf03ca4926d1b4758) Executor can access the k8s apiserver with a out-of-cluster config file (#1134)
 * [0bda53c7](https://github.com/argoproj/argo-workflows/commit/0bda53c77c54b037e7d91b18554053362b1e4d35) fix dag retries (#1221)
 * [8aae2931](https://github.com/argoproj/argo-workflows/commit/8aae29317a8cfef2edc084a4c74a44c83d845936) Issue #1190 - Fix incorrect retry node handling (#1208)
 * [f1797f78](https://github.com/argoproj/argo-workflows/commit/f1797f78044504dbf2e1f7285cc9c18ac79f5e81) Add schedulerName to workflow and template spec (#1184)
 * [2ddae161](https://github.com/argoproj/argo-workflows/commit/2ddae161037f603d2a3c12ba6b495dc422547b58) Set executor image pull policy for resource template (#1174)
 * [edcb5629](https://github.com/argoproj/argo-workflows/commit/edcb56296255267a3c8fa639c3ad26a016caab80) Dockerfile: argoexec base image correction (fixes #1209) (#1213)
 * [f92284d7](https://github.com/argoproj/argo-workflows/commit/f92284d7108ebf92907008d8f12a0696ee467a43) Minor spelling, formatting, and style updates. (#1193)
 * [bd249a83](https://github.com/argoproj/argo-workflows/commit/bd249a83e119d6161fa1c593b09fb381db448a0d) Issue #1128 - Use polling instead of fs notify to get annotation changes (#1194)
 * [14a432e7](https://github.com/argoproj/argo-workflows/commit/14a432e75119e37d42715b7e83992789c6dac454) Update community/README (#1197)
 * [eda7e084](https://github.com/argoproj/argo-workflows/commit/eda7e08438d2314bb5eb178a1335a3c28555ab34) Updated OWNERS (#1198)
 * [73504a24](https://github.com/argoproj/argo-workflows/commit/73504a24e885c6df9d1cceb4aa123c79eca7b7cd) Fischerjulian adds ruby to rest docs (#1196)
 * [311ad86f](https://github.com/argoproj/argo-workflows/commit/311ad86f101c58a1de1cef313a1516b4c79e643f) Fix missing docker binary in argoexec image. Improve reuse of image layers
 * [831e2198](https://github.com/argoproj/argo-workflows/commit/831e2198e22503394acca1cce0dbcf8dcebb2931) Issue #988 - Submit should not print logs to stdout unless output is 'wide' (#1192)
 * [17250f3a](https://github.com/argoproj/argo-workflows/commit/17250f3a51d545c49114882d0da6ca29eda7c6f2) Add documentation how to use parameter-file's (#1191)
 * [01ce5c3b](https://github.com/argoproj/argo-workflows/commit/01ce5c3bcf0dde5536b596d48bd48a93b3f2eee0) Add Docker Hub build hooks
 * [93289b42](https://github.com/argoproj/argo-workflows/commit/93289b42f96cd49cdc048d84626cb28ef6932940) Refactor Makefile/Dockerfile to remove volume binding in favor of build stages (#1189)
 * [8eb4c666](https://github.com/argoproj/argo-workflows/commit/8eb4c66639c5fd1a607c73a4d765468a99c43da1) Issue #1123 - Fix 'kubectl get' failure if resource namespace is different from workflow namespace (#1171)
 * [eaaad7d4](https://github.com/argoproj/argo-workflows/commit/eaaad7d47257302f203bab24bce1b7d479453351) Increased S3 artifact retry time and added log (#1138)
 * [f07b5afe](https://github.com/argoproj/argo-workflows/commit/f07b5afeaf950f49f87cdffb5116e82c8b0d43a1) Issue #1113 - Wait for daemon pods completion to handle annotations (#1177)
 * [2b2651b0](https://github.com/argoproj/argo-workflows/commit/2b2651b0a7f5d6873c8470fad137d42f9b7d7240) Do not mount unnecessary docker socket (#1178)
 * [1fc03144](https://github.com/argoproj/argo-workflows/commit/1fc03144c55f987993c7777b190b1848fc3833cd) Argo users: Equinor (#1175)
 * [e381653b](https://github.com/argoproj/argo-workflows/commit/e381653b6d6d6a6babba2e8f05f6f103e81a191d) Update README. (#1173) (#1176)
 * [5a917140](https://github.com/argoproj/argo-workflows/commit/5a917140cb56a27e7b6f3b1d5068f4838863c273) Update README and preview notice in CLA.
 * [521eb25a](https://github.com/argoproj/argo-workflows/commit/521eb25aeb2b8351d72bad4a3d3aa2d1fa55eb23) Validate ArchiveLocation artifacts (#1167)
 * [528e8f80](https://github.com/argoproj/argo-workflows/commit/528e8f803683ee462ccc05fc9b00dc57858c0e93) Add missing patch in namespace kustomization.yaml (#1170)
 * [0b41ca0a](https://github.com/argoproj/argo-workflows/commit/0b41ca0a2410b01205712a2186dd12851eecb707) Add Preferred Networks to users in README.md (#1172)
 * [649d64d1](https://github.com/argoproj/argo-workflows/commit/649d64d1bd375f779cd150446bddce94582067d2) Add GitHub to users in README.md (#1151)
 * [864c7090](https://github.com/argoproj/argo-workflows/commit/864c7090a0bfcaa12237ff6e894a9d26ab463a7a) Update codegen for network config (#1168)
 * [c3cc51be](https://github.com/argoproj/argo-workflows/commit/c3cc51be2e14e931d6e212aa30842a2c514082d1) Support HDFS Artifact (#1159)
 * [8db00066](https://github.com/argoproj/argo-workflows/commit/8db0006667dec74c58cbab744b014c67fda55c65) add support for hostNetwork & dnsPolicy config (#1161)
 * [149d176f](https://github.com/argoproj/argo-workflows/commit/149d176fdf3560d74afa91fe91a0ee38bf7ec3bd) Replace exponential retry with poll (#1166)
 * [31e5f63c](https://github.com/argoproj/argo-workflows/commit/31e5f63cba89b06abc2cdce0d778c6b8d937a23e) Fix tests compilation error (#1157)
 * [6726d9a9](https://github.com/argoproj/argo-workflows/commit/6726d9a961a2c3ed5467430d3631a36cfbf361de) Fix failing TestAddGlobalArtifactToScope unit test
 * [4fd758c3](https://github.com/argoproj/argo-workflows/commit/4fd758c38fc232bf26bb5e1d4e7e23321ba91416) Add slack badge to README (#1164)
 * [3561bff7](https://github.com/argoproj/argo-workflows/commit/3561bff70ad6bfeca8967be6aa4ac24fbbc8ac27) Issue #1136 - Fix metadata for DAG with loops (#1149)
 * [c7fec9d4](https://github.com/argoproj/argo-workflows/commit/c7fec9d41c0e2d3369e111f8b1d0f1d0ca77edae) Reflect minio chart changes in documentation (#1147)
 * [f6ce7833](https://github.com/argoproj/argo-workflows/commit/f6ce78334762cbc3c6de1604c11ea4f5f618c275) add support for other archs (#1137)
 * [cb538489](https://github.com/argoproj/argo-workflows/commit/cb538489a187134577e2146afcf9367f45088ff7) Fix issue where steps with exhausted retires would not complete (#1148)
 * [e400b65c](https://github.com/argoproj/argo-workflows/commit/e400b65c5eca2de2aa891f8489dcd835ef0e161c) Fix global artifact overwriting in nested workflow (#1086)
 * [174eb20a](https://github.com/argoproj/argo-workflows/commit/174eb20a6a110c9bf647b040460df83b6ab031c4) Issue #1040 - Kill daemoned step if workflow consist of single daemoned step (#1144)
 * [e078032e](https://github.com/argoproj/argo-workflows/commit/e078032e469effdfc492c8eea97eb2701ceda0c2) Issue #1132 - Fix panic in ttl controller (#1143)
 * [e09d9ade](https://github.com/argoproj/argo-workflows/commit/e09d9ade25535ae7e78ca23636e4d158a98bba84) Issue #1104 - Remove container wait timeout from 'argo logs --follow' (#1142)
 * [0f84e514](https://github.com/argoproj/argo-workflows/commit/0f84e5148dd34c225a35eab7a1f5953afb45e724) Allow owner reference to be set in submit util (#1120)
 * [3484099c](https://github.com/argoproj/argo-workflows/commit/3484099c856716f6da5e02ad75a48b568f547695) Update generated swagger to fix verify-codegen (#1131)
 * [587ab1a0](https://github.com/argoproj/argo-workflows/commit/587ab1a02772cd9b7ae7cd94f91b815ac4774297) Fix output artifact and parameter conflict (#1125)
 * [6bb3adbc](https://github.com/argoproj/argo-workflows/commit/6bb3adbc596349100c4f19155cfe976f4ea0e6fb) Adding Quantibio in Who uses Argo (#1111)
 * [1ae3696c](https://github.com/argoproj/argo-workflows/commit/1ae3696c27f343c947d9225c5cc2294c8b7c45e5) Install mime-support in argoexec to set proper mime types for S3 artifacts (resolves #1119)
 * [515a9005](https://github.com/argoproj/argo-workflows/commit/515a9005057dfd260a8b60c4ba1ab8c3aa614f48) add support for ppc64le and s390x (#1102)
 * [78142837](https://github.com/argoproj/argo-workflows/commit/78142837836cb100f6858d246d84100b74794cc6) Remove docker_lib mount volume which is not needed anymore (#1115)
 * [e59398ad](https://github.com/argoproj/argo-workflows/commit/e59398adf39b8ef1d0ce273263e80d49e370c510) Fix examples docs of parameters. (#1110)
 * [ec20d94b](https://github.com/argoproj/argo-workflows/commit/ec20d94b6f1d0d88d579c8a27b964f6e9915ff55) Issue #1114 - Set FORCE_NAMESPACE_ISOLATION env variable in namespace install manifests (#1116)
 * [49c1fa4f](https://github.com/argoproj/argo-workflows/commit/49c1fa4f42e1c19ce3b8f4ac2c339894e1ed90d7) Update docs with examples using the K8s REST API
 * [bb8a6a58](https://github.com/argoproj/argo-workflows/commit/bb8a6a58fee8170d6db65c73a50c5fe640f3cb7d) Update ROADMAP.md
 * [46855dcd](https://github.com/argoproj/argo-workflows/commit/46855dcde1d9ba904a1c94a97e602d0510f5e0d4) adding logo to be used by the OS Site (#1099)
 * [438330c3](https://github.com/argoproj/argo-workflows/commit/438330c38da69a68d6b0b0b24f6aae0053fc35ee) #1081 added retry logic to s3 load and save function (#1082)
 * [cb8b036b](https://github.com/argoproj/argo-workflows/commit/cb8b036b8db3ebeb6ef73d9f2070a1ddaf0d2150) Initialize child node before marking phase. Fixes panic on invalid `When` (#1075)
 * [60b508dd](https://github.com/argoproj/argo-workflows/commit/60b508dd9ec36ef45013d72ec6166dd9a30d77fe) Drop reference to removed `argo install` command. (#1074)
 * [62b24368](https://github.com/argoproj/argo-workflows/commit/62b24368a93d57eb505bf226e042a8eb0bf72da4) Fix typo in demo.md (#1089)
 * [b5dfa021](https://github.com/argoproj/argo-workflows/commit/b5dfa0217470c97d8e83716a22cf3bd274c4a2d5) Use relative links on README file (#1087)
 * [95b72f38](https://github.com/argoproj/argo-workflows/commit/95b72f38c94d12735e79bb8bec1a46b10514603c) Update docs to outline bare minimum set of privileges for a workflow
 * [d4ef6e94](https://github.com/argoproj/argo-workflows/commit/d4ef6e944c302b5d2b75d4c49e1833c3a28c1f9a) Add new article and minor edits. (#1083)
 * [afdac9bb](https://github.com/argoproj/argo-workflows/commit/afdac9bb34fe8a01ad511323a00ccf6c07e41137) Issue #740 - System level workflow parallelism limits & priorities (#1065)
 * [a53a76e9](https://github.com/argoproj/argo-workflows/commit/a53a76e9401fab701eaa150307b21a28825c97ce) fix #1078 Azure AKS authentication issues (#1079)
 * [79b3e307](https://github.com/argoproj/argo-workflows/commit/79b3e30746f779e3cec3a28beaecb9c0df7024e1) Fix string format arguments in workflow utilities. (#1070)
 * [76b14f54](https://github.com/argoproj/argo-workflows/commit/76b14f54520a92b81ced78d4cae2632655f396fc) Auto-complete workflow names (#1061)
 * [f2914d63](https://github.com/argoproj/argo-workflows/commit/f2914d63e9c8b41a13b5932f7962f208b7e5a0da) Support nested steps workflow parallelism (#1046)
 * [eb48c23a](https://github.com/argoproj/argo-workflows/commit/eb48c23a2525a62bbc1b8b4c94e3d50fd91014bd) Raise not implemented error when artifact saving is unsupported (#1062)
 * [036969c0](https://github.com/argoproj/argo-workflows/commit/036969c0f4f6ce6a3c948b5d161c0367cf07176b) Add Cratejoy to list of users (#1063)
 * [a07bbe43](https://github.com/argoproj/argo-workflows/commit/a07bbe431cecbb1d50356f94111d3bd2dbc48bb6) Adding SAP Hybris in Who uses Argo (#1064)
 * [7ef1cea6](https://github.com/argoproj/argo-workflows/commit/7ef1cea68c94f7f0e1e2f8bd75bedc5a7df8af90) Update dependencies to K8s v1.12 and client-go 9.0
 * [23d733ba](https://github.com/argoproj/argo-workflows/commit/23d733bae386db44ec80639daf91b29dbf86b335) Add namespace explicitly to pod metadata (#1059)
 * [79ed7665](https://github.com/argoproj/argo-workflows/commit/79ed7665d7419e7fbfe8b120c4cbcd486bebee57) Parameter and Argument names should support snake case (#1048)
 * [6e6c59f1](https://github.com/argoproj/argo-workflows/commit/6e6c59f13ff84fd6b4f1e7f836c783941c434ce7) Submodules are dirty after checkout -- need to update (#1052)
 * [f18716b7](https://github.com/argoproj/argo-workflows/commit/f18716b74c6f52d0c8bf4d64c05eae9db75bfb1f) Support for K8s API based Executor (#1010)
 * [e297d195](https://github.com/argoproj/argo-workflows/commit/e297d19501a8116b5a18c925a3c72d7c7e106ea0) Updated examples/README.md (#1051)
 * [19d6cee8](https://github.com/argoproj/argo-workflows/commit/19d6cee8149917c994b737510d9c8dbfc6dbdd27) Updated ARTIFACT_REPO.md (#1049)

### Contributors

 * Adrien Trouillaud
 * Alexander Matyushentsev
 * Alexey Volkov
 * Andrei Miulescu
 * Anna Winkler
 * Bastian Echterhölter
 * Chen Zhiwei
 * Chris Chambers
 * Clemens Lange
 * Daisuke Taniwaki
 * Dan Norris
 * Divya Vavili
 * Ed Lee
 * Edward Lee
 * Erik Parmann
 * Fred Dubois
 * Greg Roodt
 * Hamel Husain
 * Hideto Inamura
 * Howie Benefiel
 * Ian Howell
 * Ilias K
 * Ilias Katsakioris
 * Ismail Alidzhikov
 * Jesse Suen
 * Johannes 'fish' Ziemke
 * Joshua Carp
 * Julian Fischer
 * Konstantin Zadorozhny
 * Marcin Karkocha
 * Matthew Coleman
 * Miyamae Yuuya
 * Naoto Migita
 * Naresh Kumar Amrutham
 * Nick Stott
 * Pengfei Zhao
 * Rocio Montes
 * Saravanan Balasubramanian
 * Tang Lee
 * Tim Schrodi
 * Val Sichkovskyi
 * WeiYan
 * Xianlu Bird
 * almariah
 * gerardaus
 * houz
 * jacky
 * jdfalko
 * kshamajain99
 * shahin
 * xubofei1983

## v2.2.1 (2018-10-11)

 * [0a928e93](https://github.com/argoproj/argo-workflows/commit/0a928e93dac6d8522682931a0a68c52add310cdb) Update installation manifests to use v2.2.1
 * [3b52b261](https://github.com/argoproj/argo-workflows/commit/3b52b26190163d1f72f3aef1a39f9f291378dafb) Fix linter warnings and update swagger
 * [7d0e77ba](https://github.com/argoproj/argo-workflows/commit/7d0e77ba74587d913b1f4aceb1443228a04d35de) Update changelog and bump version to 2.2.1
 * [b402e12f](https://github.com/argoproj/argo-workflows/commit/b402e12feefe5cd1380e9479b2cc9bae838357bf) Issue #1033 - Workflow executor panic: workflows.argoproj.io/template workflows.argoproj.io/template not found in annotation file (#1034)
 * [3f2e986e](https://github.com/argoproj/argo-workflows/commit/3f2e986e130ca136514767fb1593d745ca418236) fix typo in examples/README.md (#1025)
 * [9c5e056a](https://github.com/argoproj/argo-workflows/commit/9c5e056a858a9b510cdacdbc5deb5857a97662f8) Replace tabs with spaces (#1027)
 * [091f1407](https://github.com/argoproj/argo-workflows/commit/091f1407180990c745e981b24169c3bb4868dbe3) Update README.md (#1030)
 * [159fe09c](https://github.com/argoproj/argo-workflows/commit/159fe09c99c16738c0897f9d74087ec1b264954d) Fix format issues to resolve build errors (#1023)
 * [363bd97b](https://github.com/argoproj/argo-workflows/commit/363bd97b72ae5cb7fc52a560b6f7939248cdb72d) Fix error in env syntax (#1014)
 * [ae7bf0a5](https://github.com/argoproj/argo-workflows/commit/ae7bf0a5f7ddb1e5211e724bef15951198610942) Issue #1018 - Workflow controller should save information about archived logs in step outputs (#1019)
 * [15d006c5](https://github.com/argoproj/argo-workflows/commit/15d006c54ee7149b0d86e6d60453ecc8c071c953) Add example of workflow using imagePullSecrets (resolves #1013)
 * [2388294f](https://github.com/argoproj/argo-workflows/commit/2388294fa412e153d8366910e4d47ba564f29856) Fix RBAC roles to include workflow delete for GC to work properly (resolves #1004)
 * [6f611cb9](https://github.com/argoproj/argo-workflows/commit/6f611cb9383610471f941b5cab4227ce8bfea7c5) Fix issue where resubmission of a terminated workflow creates a terminated workflow (issue #1011)
 * [4a7748f4](https://github.com/argoproj/argo-workflows/commit/4a7748f433f888fdc50b592db1002244ea466bdb) Disable Persistence in the demo example (#997)
 * [55ae0cb2](https://github.com/argoproj/argo-workflows/commit/55ae0cb242a9cf6b390822ca6c0aa0868f5b06e3) Fix example pod name (#1002)
 * [c275e7ac](https://github.com/argoproj/argo-workflows/commit/c275e7acb7b5e8f9820a09d8b0cb635f710b8674) Add imagePullPolicy config for executors (#995)
 * [b1eed124](https://github.com/argoproj/argo-workflows/commit/b1eed124e6d943c453d87a9b4291ba10198d0bc6) `tar -tf` will detect compressed tars correctly. (#998)
 * [03a7137c](https://github.com/argoproj/argo-workflows/commit/03a7137c9ca9459727b57fb0a0e95584c5305844) Add new organization using argo (#994)
 * [83884528](https://github.com/argoproj/argo-workflows/commit/8388452870ed9a2d2e348a2844d3d7d1c4d61b05) Update argoproj/pkg to trim leading/trailing whitespace in S3 credentials (resolves #981)
 * [978b4938](https://github.com/argoproj/argo-workflows/commit/978b49383d30cdbc7c9708eb281b7800ee5412df) Add syntax highlighting for all YAML snippets and most shell snippets (#980)
 * [60d5dc11](https://github.com/argoproj/argo-workflows/commit/60d5dc11c73e888898160b4cc329e87747cee4d2) Give control to decide whether or not to archive logs at a template level
 * [8fab73b1](https://github.com/argoproj/argo-workflows/commit/8fab73b142b96f943592c66932ae0c5183e8c3db) Detect and indicate when container was OOMKilled
 * [47a9e556](https://github.com/argoproj/argo-workflows/commit/47a9e5560229c789b70a6624f23fb4433412fbc4) Update config map doc with instructions to enable log archiving
 * [79dbbaa1](https://github.com/argoproj/argo-workflows/commit/79dbbaa1ed30cae6279eabd9a84650107f4387b3) Add instructions to match git URL format to auth type in git example (issue #979)
 * [429f03f5](https://github.com/argoproj/argo-workflows/commit/429f03f5b26db42f1857a93b7599b545642c2f0a) Add feature list to README.md. Tweaks to getting started.
 * [36fd1948](https://github.com/argoproj/argo-workflows/commit/36fd19482c6bebfb21076cba81b924deaff14f52) Update getting started guide with v2.2.0 instructions

### Contributors

 * Alexander Matyushentsev
 * Appréderisse Benjamin
 * Daisuke Taniwaki
 * David Bernard
 * Feynman Liang
 * Ilya Sotkov
 * Jesse Suen
 * Marco Sanvido
 * Matt Hillsdon
 * Sean Fern
 * WeiYan

## v2.2.0 (2018-08-30)

 * [af636ddd](https://github.com/argoproj/argo-workflows/commit/af636ddd8455660f307d835814d3112b90815dfd) Update installation manifests to use v2.2.0
 * [7864ad36](https://github.com/argoproj/argo-workflows/commit/7864ad36788dc78d035d59ddb27ecd979f7216f4) Introduce `withSequence` to iterate a range of numbers in a loop (resolves #527)
 * [99e9977e](https://github.com/argoproj/argo-workflows/commit/99e9977e4ccf61171ca1e347f6a182ba1d8dba83) Introduce `argo terminate` to terminate a workflow without deleting it (resolves #527)
 * [f52c0450](https://github.com/argoproj/argo-workflows/commit/f52c045087abff478603db4817de1933bddce5e7) Reorganize codebase to make CLI functionality available as a library
 * [311169f7](https://github.com/argoproj/argo-workflows/commit/311169f7e71c58fe9bf879a94681ee274ddf623c) Fix issue where sidecars and daemons were not reliably killed (resolves #879)
 * [67ffb6eb](https://github.com/argoproj/argo-workflows/commit/67ffb6eb7519936e1149f36e11dc9fda0f70a242) Add a reason/message for Unschedulable Pending pods
 * [69c390f2](https://github.com/argoproj/argo-workflows/commit/69c390f288ccaaeefba1d5a7961acebfe2e7771a) Support for workflow level timeouts (resolves #848)
 * [f88732ec](https://github.com/argoproj/argo-workflows/commit/f88732ec09413716bf14927bef10355b21b88516) Update docs to use keyFormat field
 * [0df022e7](https://github.com/argoproj/argo-workflows/commit/0df022e777f35bf0ea39ebbacfe4e5f92f099a62) Rename keyPattern to keyFormat. Remove pending pod query during pod reconciliation
 * [75a9983b](https://github.com/argoproj/argo-workflows/commit/75a9983b17869b76a93621f108ee85c70b8d8533) Fix potential panic in `argo watch`
 * [9cb46449](https://github.com/argoproj/argo-workflows/commit/9cb4644975d16dbebc3607ffb91364c93bc14e30) Add TTLSecondsAfterFinished field and controller to garbage collect completed workflows (resolves #911)
 * [7540714a](https://github.com/argoproj/argo-workflows/commit/7540714a47f04f664362c7083c886058c62408f8) Add ability to archive container logs to the artifact repository (resolves #454)
 * [11e57f4d](https://github.com/argoproj/argo-workflows/commit/11e57f4dea93fde60b204a5e7675fec999c66f56) Introduce archive strategies with ability to disable tar.gz archiving (resolves #784)
 * [e180b547](https://github.com/argoproj/argo-workflows/commit/e180b547133aa461bd5cc282a59f8954485d5b8f) Update CHANGELOG.md
 * [5670bf5a](https://github.com/argoproj/argo-workflows/commit/5670bf5a65cbac898b298edd682e603666ed5cb6) Introduce `argo watch` command to watch live workflows from terminal (resolves #969)
 * [57394361](https://github.com/argoproj/argo-workflows/commit/5739436199980ec765b070f8e78669bc37115ad6) Support additional container runtimes through kubelet executor (#952)
 * [a9c84c97](https://github.com/argoproj/argo-workflows/commit/a9c84c97de8f088cd4ee91cd72cf75012fc70438) Error workflows which hit k8s/etcd 1M resource size limit (resolves #913)
 * [67792eb8](https://github.com/argoproj/argo-workflows/commit/67792eb89e5aa678ffc52540dbc232d8598ce43f) Add parameter-file support (#966)
 * [841832a3](https://github.com/argoproj/argo-workflows/commit/841832a3507be3b92e3b2a05fef1052b1cd6e20d) Aggregate workflow RBAC roles to built-in admin/edit/view clusterroles (resolves #960)
 * [35bb7093](https://github.com/argoproj/argo-workflows/commit/35bb70936cf1b76e53f7f6f0e6acaccb9c6d06bf) Allow scaling of workflow and pod workers via controller CLI flags (resolves #962)
 * [b479fa10](https://github.com/argoproj/argo-workflows/commit/b479fa10647bd1c1b86410b7837668c375b327be) Improve workflow configmap documentation for keyPattern
 * [f1802f91](https://github.com/argoproj/argo-workflows/commit/f1802f91d8934b2e4b9d1f64230230bc2a0b5baf) Introduce `keyPattern` workflow config to enable flexibility in archive location path (issue #953)
 * [a5648a96](https://github.com/argoproj/argo-workflows/commit/a5648a9644fcea5f498c24a573a038290b92016f) Fix kubectl proxy link for argo-ui Service (#963)
 * [09f05912](https://github.com/argoproj/argo-workflows/commit/09f0591205ec81b4ec03f0f5c534a13648346f41) Introduce Pending node state to highlight failures when start workflow pods
 * [a3ff464f](https://github.com/argoproj/argo-workflows/commit/a3ff464f67a862d4110848d94a46be39876ce57e) Speed up CI job
 * [88627e84](https://github.com/argoproj/argo-workflows/commit/88627e842c082ddc4d75d15a3e2dc6c7ab4f1db8) Update base images to debian:9.5-slim. Use stable metalinter
 * [753c5945](https://github.com/argoproj/argo-workflows/commit/753c5945b62be209f05025c2e415a0753f5e0b01) Update argo-ci-builder image with new dependencies
 * [674b61bb](https://github.com/argoproj/argo-workflows/commit/674b61bb473787a157e543c10dcf158fa35bb39a) Remove unnecessary dependency on argo-cd and obsolete RBAC constants
 * [60658de0](https://github.com/argoproj/argo-workflows/commit/60658de0cf7403c4be014e92b7a3bb4772f4ad5f) Refactor linting/validation into standalone package. Support linting of .json files
 * [f55d579a](https://github.com/argoproj/argo-workflows/commit/f55d579a9478ed33755874f24656faec04611777) Detect and fail upon unknown fields during argo submit & lint (resolves #892)
 * [edf6a574](https://github.com/argoproj/argo-workflows/commit/edf6a5741de8bdf3a20852a55581883f1ec80d9a) Migrate to using argoproj.io/pkg packages
 * [5ee1e0c7](https://github.com/argoproj/argo-workflows/commit/5ee1e0c7daed4e2c8dca5643a800292ece067fca) Update artifact config docs (#957)
 * [faca49c0](https://github.com/argoproj/argo-workflows/commit/faca49c009bead218ee974bfad2ccc36f84de1fb) Updated README
 * [936c6df7](https://github.com/argoproj/argo-workflows/commit/936c6df7eaae08082c1cc7ad750f664ff8a4c54c) Add table of content to examples (#956)
 * [d2c03f67](https://github.com/argoproj/argo-workflows/commit/d2c03f67c2fd45ff54c04db706c9ebf252fca6f2) Correct image used in install manifests
 * [ec3b7be0](https://github.com/argoproj/argo-workflows/commit/ec3b7be065aa65aae207bd34930001b593009b80) Remove CLI installer/uninstaller. Executor image configured via CLI argument (issue #928) Remove redundant/unused downward API metadata
 * [3a85e242](https://github.com/argoproj/argo-workflows/commit/3a85e2429154a4d97c8fc7c92f9e8f482de6639f) Rely on `git checkout` instead of go-git checkout for more reliable revision resolution
 * [ecef0e3d](https://github.com/argoproj/argo-workflows/commit/ecef0e3dd506eefc222c1ebed58ab81265ac9638) Rename Prometheus metrics (#948)
 * [b9cffe9c](https://github.com/argoproj/argo-workflows/commit/b9cffe9cd7b347905a42cf3e217cc3b039bdfb3f) Issue #896 - Prometheus metrics and telemetry (#935)
 * [290dee52](https://github.com/argoproj/argo-workflows/commit/290dee52bfb94679870cee94ca9560bbe8bd7813) Support parameter aggregation of map results in scripts
 * [fc20f5d7](https://github.com/argoproj/argo-workflows/commit/fc20f5d787ed11f03a24439c042b9ef45349eb95) Fix errors when submodules are from different URL (#939)
 * [b4f1a00a](https://github.com/argoproj/argo-workflows/commit/b4f1a00ad2862e6545dd4ad16279a49cd4585676) Add documentation about workflow variables
 * [4a242518](https://github.com/argoproj/argo-workflows/commit/4a242518c6ea81cd0d1e5aaab2822231d9b36d46) Update readme.md (#943)
 * [a5baca60](https://github.com/argoproj/argo-workflows/commit/a5baca60d1dfb8fb8c82a936ab383d49e075cff3) Support referencing of global workflow artifacts (issue #900)
 * [9b5c8563](https://github.com/argoproj/argo-workflows/commit/9b5c85631765285b4593b7707ede014178f77679) Support for sophisticated expressions in `when` conditionals (issue #860)
 * [ecc0f027](https://github.com/argoproj/argo-workflows/commit/ecc0f0272f2257600abab8f4779c478957644d7c) Resolve revision added ability to specify shorthand revision and other things like HEAD~2 etc (#936)
 * [11024318](https://github.com/argoproj/argo-workflows/commit/11024318c0e2a9106f8a8b4a719daba12adf9f36) Support conditions with DAG tasks. Support aggregated outputs from scripts (issue #921)
 * [d07c1d2f](https://github.com/argoproj/argo-workflows/commit/d07c1d2f3b7c916887185eea749db2278bf9d043) Support withItems/withParam and parameter aggregation with DAG templates (issue #801)
 * [94c195cb](https://github.com/argoproj/argo-workflows/commit/94c195cb014ba2e5c5943d96dc0a3cc3243edb6a) Bump VERSION to v2.2.0
 * [9168c59d](https://github.com/argoproj/argo-workflows/commit/9168c59dc486f840dc2b9713d92c14bdccebbaf8) Fix outbound node metadata with retry nodes causing disconnected nodes to be rendered in UI (issue #880)
 * [c6ce48d0](https://github.com/argoproj/argo-workflows/commit/c6ce48d086638168b9bd8b998d65a2e3a4801540) Fix outbound node metadata issue with steps template causing incorrect edges to be rendered in UI
 * [520b33d5](https://github.com/argoproj/argo-workflows/commit/520b33d5fc6e7e670c33015fd74c5a2f3bd74a21) Add ability to aggregate and reference output parameters expanded by loops (issue #861)
 * [ece1eef8](https://github.com/argoproj/argo-workflows/commit/ece1eef85ac1f92d2fad8a2fef8c657f04b4599a) Support submission of workflows as json, and from stdin (resolves #926)
 * [4c31d61d](https://github.com/argoproj/argo-workflows/commit/4c31d61da2891e92a3ae0d09b6924655a07fc59f) Add `argo delete --older` to delete completed workflows older than specified duration (resolves #930)
 * [c87cd33c](https://github.com/argoproj/argo-workflows/commit/c87cd33c1bc46c06314129c882fec80269af8133) Update golang version to v1.10.3
 * [618b7eb8](https://github.com/argoproj/argo-workflows/commit/618b7eb84678e177a38e5aa81fa59ed891459aa5) Proper fix for assessing overall DAG phase. Add some DAG unit tests (resolves #885)
 * [f223e5ad](https://github.com/argoproj/argo-workflows/commit/f223e5ad62115399cf1394db4e9e65f05ae6da8b) Fix issue where a DAG would fail even if retry was successful (resolves #885)
 * [143477f3](https://github.com/argoproj/argo-workflows/commit/143477f3d5e0ab0d65dd97774aabdcd736ae4fbe) Start use of argoproj/pkg shared libraries
 * [1220d080](https://github.com/argoproj/argo-workflows/commit/1220d0801b8aa78c5364a4586cd119553d96bca5) Update argo-cluster-role to work with OpenShift (resolves #922)
 * [4744f45a](https://github.com/argoproj/argo-workflows/commit/4744f45a9c110b11fa73070a52e4166406fa5da4) Added SSH clone and proper git clone using go-git (#919)
 * [d657abf4](https://github.com/argoproj/argo-workflows/commit/d657abf4a37c9f2987b5cc2ee337743c981c3e48) Regenerate code and address OpenAPI rule validation errors (resolves #923)
 * [c5ec4cf6](https://github.com/argoproj/argo-workflows/commit/c5ec4cf6194ab5f741eb2e1d4e387dcf32ba3ce7) Upgrade k8s dependencies to v1.10 (resolves #908)
 * [ba8061ab](https://github.com/argoproj/argo-workflows/commit/ba8061abd296895555ea3d1d6ca7418fcd07d633) Redundant verifyResolvedVariables check in controller precluded the ability to use {{ }} in other circumstances
 * [05a61449](https://github.com/argoproj/argo-workflows/commit/05a614496bb921b5fa081605227de1a8832260cd) Added link to community meetings (#912)
 * [f33624d6](https://github.com/argoproj/argo-workflows/commit/f33624d67d0cf348dcdece46832081346c26bf80) Add an example on how to submit and wait on a workflow
 * [aeed7f9d](https://github.com/argoproj/argo-workflows/commit/aeed7f9da490d8dc4ad40c00ac2272a19da4ff17) Added new members
 * [288e4fc8](https://github.com/argoproj/argo-workflows/commit/288e4fc8577890e7fa6cc546f92aef4c954ce18c) Added Argo Events link.
 * [3322506e](https://github.com/argoproj/argo-workflows/commit/3322506e5a1d07e198f69cadd210b0b6cc6cfbc9) Updated README
 * [3ce640a2](https://github.com/argoproj/argo-workflows/commit/3ce640a24509454302a5126c972fd5424673c00e) Issue #889 - Support retryStrategy for scripts (#890)
 * [91c6afb2](https://github.com/argoproj/argo-workflows/commit/91c6afb2cc07c113e4999f114279638aa6809fd6) adding BlackRock as corporate contributor/user (#886)
 * [c8667b5c](https://github.com/argoproj/argo-workflows/commit/c8667b5c81068326638a5e35c20336223b3894db) Fix issue where `argo lint` required spec level arguments to be supplied
 * [ed7dedde](https://github.com/argoproj/argo-workflows/commit/ed7dedde1f8be2a5f7be828a31ac9bb4025919e1) Update influx-ci example to choose a stable InfluxDB branch
 * [135813e1](https://github.com/argoproj/argo-workflows/commit/135813e10e932a2187d007284766a816d9aa4442) Add datadog to the argo users (#882)
 * [f1038948](https://github.com/argoproj/argo-workflows/commit/f103894843e9ed8cbaf4212e765c10311bec5989) Fix `make verify-codegen` build target when run in CI
 * [785f2cbd](https://github.com/argoproj/argo-workflows/commit/785f2cbd114e6d0097e21240d5cacece0b6d071e) Update references to v2.1.1. Add better checks in release Makefile target
 * [d65e1cd3](https://github.com/argoproj/argo-workflows/commit/d65e1cd3e77efbe6fc877ac689fd4cd19bc35093) readme: add Interline Technologies to user list (#867)
 * [c903168e](https://github.com/argoproj/argo-workflows/commit/c903168ee12f296f71f4953cda2163b8fa8cd409) Add documentation on global parameters (#871)

### Contributors

 * Andrei Miulescu
 * David Van Loon
 * Drew Dara-Abrams
 * Ed Lee
 * Edward Lee
 * Jesse Suen
 * Julien Balestra
 * Konstantin Zadorozhny
 * Matthew Magaldi
 * Nándor István Krácser
 * Val Sichkovskyi
 * Vincent Smith
 * dthomson25

## v2.1.2 (2018-10-11)

 * [b82ce5b0](https://github.com/argoproj/argo-workflows/commit/b82ce5b0b558ec5df70b760c0f67fc7e84cdfdf1) Update version to 2.1.2
 * [01a1214e](https://github.com/argoproj/argo-workflows/commit/01a1214e6ae6680663168d308399b11aa7224d7e) Issue #1033 - Workflow executor panic: workflows.argoproj.io/template workflows.argoproj.io/template not found in annotation file (#1034)

### Contributors

 * Alexander Matyushentsev

## v2.1.1 (2018-05-29)

 * [ac241c95](https://github.com/argoproj/argo-workflows/commit/ac241c95c13f08e868cd6f5ee32c9ce273e239ff) Update CHANGELOG for v2.1.1
 * [468e0760](https://github.com/argoproj/argo-workflows/commit/468e07600c5e124c8d2e0737f8c67a3265979952) Retrying failed steps templates could potentially result in disconnected children
 * [8d96ea7b](https://github.com/argoproj/argo-workflows/commit/8d96ea7b1b1ba843eb19a0632bc503d816ab9ef3) Switch to an UnstructuredInformer to guard against malformed workflow manifests (resolves #632)
 * [5bef6cae](https://github.com/argoproj/argo-workflows/commit/5bef6cae26dece96cadad855c9d54c5148f5e917) Suspend templates were not properly being connected to their children (resolves #869)
 * [543e9392](https://github.com/argoproj/argo-workflows/commit/543e9392f44873d1deb0a95fad3e00d67e8a7c70) Fix issue where a failed step in a template with parallelism would not complete (resolves #868)
 * [289000ca](https://github.com/argoproj/argo-workflows/commit/289000cac81b199c2fc9e50d04831e3ccfcc0659) Update argocli Dockerfile and make cli-image part of release
 * [d35a1e69](https://github.com/argoproj/argo-workflows/commit/d35a1e6949beca7cd032e5de5687e4e66869a916) Bump version to v2.1.1
 * [bbcff0c9](https://github.com/argoproj/argo-workflows/commit/bbcff0c94edf2b3270d7afc03b2538f47cb28492) Fix issue where `argo list` age column maxed out at 1d (resolves #857)
 * [d68cfb7e](https://github.com/argoproj/argo-workflows/commit/d68cfb7e585121e38e36c9d9dbd3e9cf8a1d9aac) Fix issue where volumes were not supported in script templates (resolves #852)
 * [fa72b6db](https://github.com/argoproj/argo-workflows/commit/fa72b6dbe4533ed9e2cc2c9f6bb574bcd85c6d16) Fix implementation of DAG task targets (resolves #865)
 * [dc003f43](https://github.com/argoproj/argo-workflows/commit/dc003f43baeba5509bfadfc825ced533715b93c6) Children of nested DAG templates were not correctly being connected to its parent
 * [b8065797](https://github.com/argoproj/argo-workflows/commit/b8065797712a29b0adefa5769cc6ffd2c6c7edd7) Simplify some examples for readability and clarity
 * [7b02c050](https://github.com/argoproj/argo-workflows/commit/7b02c050e86138983b20a38ee9efab52180141d5) Add CoreFiling to "Who uses Argo?" section. (#864)
 * [4f2fde50](https://github.com/argoproj/argo-workflows/commit/4f2fde505d221783bec889f3c9339361f5e8be73) Add windows support for argo-cli (#856)
 * [703241e6](https://github.com/argoproj/argo-workflows/commit/703241e60c7203550ac9f7947284e5d6fde3dc74) Updated ROADMAP.md for v2.2
 * [54f2138e](https://github.com/argoproj/argo-workflows/commit/54f2138ef83f92d2038ebf7b925bd102bc5a7b8d) Spell check the examples README (#855)
 * [f23feff5](https://github.com/argoproj/argo-workflows/commit/f23feff5e9353b4796ad4f0afa33efcb1b9f0d95) Mkbranch (#851)
 * [628b5408](https://github.com/argoproj/argo-workflows/commit/628b540891d1999c708accf064356d4dad22c7e0) DAG docs. (#850)
 * [22f62439](https://github.com/argoproj/argo-workflows/commit/22f624396c3c8cacd288040935feb7da4e4a869d) Small edit to README
 * [edc09afc](https://github.com/argoproj/argo-workflows/commit/edc09afc332c6e2707688a050060548940eca852) Added OWNERS file
 * [530e7244](https://github.com/argoproj/argo-workflows/commit/530e72444e2ced0c3c050e3238431dc32c1645c5) Update release notes and documentation for v2.1.0
 * [93796381](https://github.com/argoproj/argo-workflows/commit/9379638189cc194f1b34ff7295f0832eac1c1651) Avoid `println` which outputs to stderr. (#844)
 * [30e472e9](https://github.com/argoproj/argo-workflows/commit/30e472e9495f264676c00875e4ba5ddfcc23e15f) Add gladly as an official argo user (#843)
 * [cb4c1a13](https://github.com/argoproj/argo-workflows/commit/cb4c1a13b8c92d2bbfb73c2f1d7c8fcc5697ec6b) Add ability to override metadata.name and/or metadata.generateName during submission (resolves #836)
 * [834468a5](https://github.com/argoproj/argo-workflows/commit/834468a5d12598062b870c073f9a0230028c71b0) Command print the logs for a container in a workflow
 * [1cf13f9b](https://github.com/argoproj/argo-workflows/commit/1cf13f9b008ae41bbb23af6b55bf8e982723292f) Issue #825 - fix locating outbound nodes for skipped node (#842)
 * [30034d42](https://github.com/argoproj/argo-workflows/commit/30034d42b4f35729dd4575153c268565efef47be) Bump from debian:9.1 to debian:9.4. (#841)
 * [f3c41717](https://github.com/argoproj/argo-workflows/commit/f3c41717b21339157b6519b86e22a5e20feb2b97) Owner reference example (#839)
 * [191f7aff](https://github.com/argoproj/argo-workflows/commit/191f7aff4b619bc6796c18c39e58ed9636865cf5) Minor edit to README
 * [c8a2e25f](https://github.com/argoproj/argo-workflows/commit/c8a2e25fa6085587018f65a0fc4ec31f012c2653) Fixed typo (#835)
 * [cf13bf0b](https://github.com/argoproj/argo-workflows/commit/cf13bf0b35ebbcefce1138fa77f04b268ccde394) Added users section to README
 * [e4d76329](https://github.com/argoproj/argo-workflows/commit/e4d76329bf13e72f09433a9ab219f9c025d232a9) Updated News in README
 * [b631d0af](https://github.com/argoproj/argo-workflows/commit/b631d0af4dee5ecbe6e70e39ad31b9f708efb6b9) added community meeting (#834)
 * [e34728c6](https://github.com/argoproj/argo-workflows/commit/e34728c66bf37b76cb92f03552a2f2a200f09644) Fix issue where daemoned steps were not terminated properly in DAG templates (resolves #832)
 * [2e9e113f](https://github.com/argoproj/argo-workflows/commit/2e9e113fb3f2b86f75df9669f4bf11fca181a348) Update docs to work with latest minio chart
 * [ea95f191](https://github.com/argoproj/argo-workflows/commit/ea95f191047dd17bbcab8573541d25fbd51829c0) Use octal syntax for mode values (#833)
 * [5fc67d2b](https://github.com/argoproj/argo-workflows/commit/5fc67d2b785ac582a03e7dcdc83fc212839863d1) Updated community docs
 * [8fa4f006](https://github.com/argoproj/argo-workflows/commit/8fa4f0063893d8c419e4a9466abbc608c5c97811) Added community docs
 * [423c8d14](https://github.com/argoproj/argo-workflows/commit/423c8d144eab054acf682127c1ca04c216199db0) Issue #830 - retain Step node children references
 * [73990c78](https://github.com/argoproj/argo-workflows/commit/73990c787b08f2ce72f65b8169e9f1653b5b6877) Moved cricket gifs to a different s3 bucket
 * [ca1858ca](https://github.com/argoproj/argo-workflows/commit/ca1858caade6385f5424e16f53da5d38f2fcb3b2) edit Argo license info so that GitHub recognizes it (#823)
 * [206451f0](https://github.com/argoproj/argo-workflows/commit/206451f066924abf3b4b6756606234150bf10fc9) Fix influxdb-ci.yml example
 * [da582a51](https://github.com/argoproj/argo-workflows/commit/da582a5194056a08d5eef95c2441b562cde08740) Avoid nil pointer for 2.0 workflows. (#820)
 * [0f225cef](https://github.com/argoproj/argo-workflows/commit/0f225cef91f4b276e24270a827c37dcd5292a4f0) ClusterRoleBinding was using incorrect service account namespace reference when overriding install namespace (resolves #814)
 * [66ea711a](https://github.com/argoproj/argo-workflows/commit/66ea711a1c7cc805282fd4065e029287f4617d57) Issue #816 - fix updating outboundNodes field of failed step group node (#817)
 * [00ceef6a](https://github.com/argoproj/argo-workflows/commit/00ceef6aa002199186475350b95ebc2d32debf14) install & uninstall commands use --namespace flag (#813)

### Contributors

 * Adam Pearse
 * Alexander Matyushentsev
 * Andrea Kao
 * Edward Lee
 * Eric
 * Javier Castellanos
 * Jesse Suen
 * Jonas Fonseca
 * Lukasz Lempart
 * Matt Hillsdon
 * Mukulikak
 * Sean Fitzgerald
 * Sebastien Doido

## v2.1.0-beta2 (2018-03-29)

 * [fe23c2f6](https://github.com/argoproj/argo-workflows/commit/fe23c2f651a61a2d7aa877a86edff9802d7b5b47) Issue #810 - `argo install`does not install argo ui (#811)
 * [28673ed2](https://github.com/argoproj/argo-workflows/commit/28673ed2f85ca39f5d9b136382ea9a87da0ca716) Update release date in change log

### Contributors

 * Alexander Matyushentsev

## v2.1.0-beta1 (2018-03-29)

 * [05e8a983](https://github.com/argoproj/argo-workflows/commit/05e8a98386ccc73a02f39357f6faed69f7d11a17) Update change log for 2.1.0-beta1 release
 * [bf38b6b5](https://github.com/argoproj/argo-workflows/commit/bf38b6b509ae3fb123e47da2570906d0262ccf67) Use socket type for hostPath to mount docker.sock (#804) (#809)
 * [37680ef2](https://github.com/argoproj/argo-workflows/commit/37680ef26585f412930694cc809d9870d655bd13) Minimal shell completion support (#807)
 * [c83ad24a](https://github.com/argoproj/argo-workflows/commit/c83ad24a6fb5eb7054af16ae2c4f95de8df3965b) Omit empty status fields. (#806)
 * [d7291a3e](https://github.com/argoproj/argo-workflows/commit/d7291a3ee3b5375f8a079b60c568380e1bb91de9) Issue #660 - Support rendering logs from all steps using 'argo logs' command (#792)
 * [7d3f1e83](https://github.com/argoproj/argo-workflows/commit/7d3f1e83d3e08b13eb705ddd74244ea29e019c1a) Minor edits to README
 * [7a4c9c1f](https://github.com/argoproj/argo-workflows/commit/7a4c9c1f9c4fbd5282c57011c0bdcd48fe10137b) Added a review to README
 * [383276f3](https://github.com/argoproj/argo-workflows/commit/383276f300e666bf133a0355f2da493997ddd6cc) Inlined LICENSE file. Renamed old license to COPYRIGHT
 * [91d0f47f](https://github.com/argoproj/argo-workflows/commit/91d0f47fec82c7cef156ac05287622adc0b0a53b) Build argo cli image (#800)
 * [3b2c426e](https://github.com/argoproj/argo-workflows/commit/3b2c426ee5ba6249fec0d0a59353bfe77cb0966c) Add ability to pass pod annotations and labels at the template level (#798)
 * [d8be0287](https://github.com/argoproj/argo-workflows/commit/d8be0287f04f1d0d3bdee60243e0742594009bc8) Add ability to use IAM role from EC2 instance for AWS S3 credentials
 * [624f0f48](https://github.com/argoproj/argo-workflows/commit/624f0f48306183da33e2ef3aecf9566bb0ad8ad3) Update CHANGELOG.md for v2.1.0-beta1 release
 * [e96a09a3](https://github.com/argoproj/argo-workflows/commit/e96a09a3911f039038ea3038bed3a8cd8d63e269) Allow spec.arguments to be not supplied during linting. Global parameters were not referencable from artifact arguments (resolves #791)
 * [018e663a](https://github.com/argoproj/argo-workflows/commit/018e663a53aeda35149ec9b8de28f26391eb688e) Fix for https://github.com/argoproj/argo/issues/739 Nested stepgroups render correctly (#790)
 * [5c5b35ba](https://github.com/argoproj/argo-workflows/commit/5c5b35ba271fb48c38bf65e386e3d8b574f49373) Fix install issue where service account was not being created
 * [88e9e5ec](https://github.com/argoproj/argo-workflows/commit/88e9e5ecb5fc9e5215033a11abf6f6ddf50db253) packr needs to run compiled in order to cross compile darwin binaries
 * [dcdf9acf](https://github.com/argoproj/argo-workflows/commit/dcdf9acf9c7c3f58b3adfbf1994a5d3e7574dd9c) Fix install tests and build failure
 * [06c0d324](https://github.com/argoproj/argo-workflows/commit/06c0d324bf93a037010186fe54e40590ea39d92c) Rewrite the installer such that manifests are maintainable
 * [a45bf1b7](https://github.com/argoproj/argo-workflows/commit/a45bf1b7558b3eb60ec65d02c166c306e7797a79) Introduce support for exported global output parameters and artifacts
 * [60c48a9a](https://github.com/argoproj/argo-workflows/commit/60c48a9aa4b4dbf4c229e273faa945e0f5982539) Introduce `argo retry` to retry a failed workflow with the same name (resolves #762) onExit and related nodes should never be executed during resubmit/retry (resolves #780)
 * [90c08bff](https://github.com/argoproj/argo-workflows/commit/90c08bffc1b12b4c7941daccbf417772f17e3704) Refactor command structure
 * [101509d6](https://github.com/argoproj/argo-workflows/commit/101509d6b5ebeb957bb7ad6e819a961a26812a0e) Abstract the container runtime as an interface to support mocking and future runtimes Trim a trailing newline from path-based output parameters (resolves #758)
 * [a3441d38](https://github.com/argoproj/argo-workflows/commit/a3441d38b9be1f75506ab91dfbac7d6546d2b900) Add ability to reference global parameters in spec level fields (resolves #749)
 * [cd73a9ce](https://github.com/argoproj/argo-workflows/commit/cd73a9ce18aae35beee5012c68f553ab0c46030d) Fix template.parallelism limiting parallelism of entire workflow (resolves #772) Refactor operator to make template execution method signatures consistent
 * [7d7b74fa](https://github.com/argoproj/argo-workflows/commit/7d7b74fa8a62c43f8891a9af1dcae71f6efdc7e0) Make {{pod.name}} available as a parameter in pod templates (resolves #744)
 * [3cf4bb13](https://github.com/argoproj/argo-workflows/commit/3cf4bb136a9857ea17921a2ec6cfd95b4b95a0d7) parse the artifactory URL before appending the artifact to the path (#774)
 * [ea1257f7](https://github.com/argoproj/argo-workflows/commit/ea1257f717676997f0efcac9086ed348613a28c7) examples: use alpine python image
 * [2114078c](https://github.com/argoproj/argo-workflows/commit/2114078c533db0ab34b2f76fe481f03eba046cc1) fix typo
 * [9f605589](https://github.com/argoproj/argo-workflows/commit/9f6055899fff0b3161bb573159b13fd337e2e35f) Fix retry-container-to-completion example
 * [07422f26](https://github.com/argoproj/argo-workflows/commit/07422f264ed62a428622505e1880d2d5787d50ae) Update CHANGELOG release date. Remove ui-image from release target

### Contributors

 * Alexander Matyushentsev
 * Dmitry Monakhov
 * Edward Lee
 * Jesse Suen
 * Johannes 'fish' Ziemke
 * Lukasz Lempart
 * Matt Hillsdon
 * Yang Pan
 * dougsc
 * gaganapplatix

## v2.1.0-alpha1 (2018-02-21)


### Contributors


## v2.1.0 (2018-04-30)

 * [93796381](https://github.com/argoproj/argo-workflows/commit/9379638189cc194f1b34ff7295f0832eac1c1651) Avoid `println` which outputs to stderr. (#844)
 * [30e472e9](https://github.com/argoproj/argo-workflows/commit/30e472e9495f264676c00875e4ba5ddfcc23e15f) Add gladly as an official argo user (#843)
 * [cb4c1a13](https://github.com/argoproj/argo-workflows/commit/cb4c1a13b8c92d2bbfb73c2f1d7c8fcc5697ec6b) Add ability to override metadata.name and/or metadata.generateName during submission (resolves #836)
 * [834468a5](https://github.com/argoproj/argo-workflows/commit/834468a5d12598062b870c073f9a0230028c71b0) Command print the logs for a container in a workflow
 * [1cf13f9b](https://github.com/argoproj/argo-workflows/commit/1cf13f9b008ae41bbb23af6b55bf8e982723292f) Issue #825 - fix locating outbound nodes for skipped node (#842)
 * [30034d42](https://github.com/argoproj/argo-workflows/commit/30034d42b4f35729dd4575153c268565efef47be) Bump from debian:9.1 to debian:9.4. (#841)
 * [f3c41717](https://github.com/argoproj/argo-workflows/commit/f3c41717b21339157b6519b86e22a5e20feb2b97) Owner reference example (#839)
 * [191f7aff](https://github.com/argoproj/argo-workflows/commit/191f7aff4b619bc6796c18c39e58ed9636865cf5) Minor edit to README
 * [c8a2e25f](https://github.com/argoproj/argo-workflows/commit/c8a2e25fa6085587018f65a0fc4ec31f012c2653) Fixed typo (#835)
 * [cf13bf0b](https://github.com/argoproj/argo-workflows/commit/cf13bf0b35ebbcefce1138fa77f04b268ccde394) Added users section to README
 * [e4d76329](https://github.com/argoproj/argo-workflows/commit/e4d76329bf13e72f09433a9ab219f9c025d232a9) Updated News in README
 * [b631d0af](https://github.com/argoproj/argo-workflows/commit/b631d0af4dee5ecbe6e70e39ad31b9f708efb6b9) added community meeting (#834)
 * [e34728c6](https://github.com/argoproj/argo-workflows/commit/e34728c66bf37b76cb92f03552a2f2a200f09644) Fix issue where daemoned steps were not terminated properly in DAG templates (resolves #832)
 * [2e9e113f](https://github.com/argoproj/argo-workflows/commit/2e9e113fb3f2b86f75df9669f4bf11fca181a348) Update docs to work with latest minio chart
 * [ea95f191](https://github.com/argoproj/argo-workflows/commit/ea95f191047dd17bbcab8573541d25fbd51829c0) Use octal syntax for mode values (#833)
 * [5fc67d2b](https://github.com/argoproj/argo-workflows/commit/5fc67d2b785ac582a03e7dcdc83fc212839863d1) Updated community docs
 * [8fa4f006](https://github.com/argoproj/argo-workflows/commit/8fa4f0063893d8c419e4a9466abbc608c5c97811) Added community docs
 * [423c8d14](https://github.com/argoproj/argo-workflows/commit/423c8d144eab054acf682127c1ca04c216199db0) Issue #830 - retain Step node children references
 * [73990c78](https://github.com/argoproj/argo-workflows/commit/73990c787b08f2ce72f65b8169e9f1653b5b6877) Moved cricket gifs to a different s3 bucket
 * [ca1858ca](https://github.com/argoproj/argo-workflows/commit/ca1858caade6385f5424e16f53da5d38f2fcb3b2) edit Argo license info so that GitHub recognizes it (#823)
 * [206451f0](https://github.com/argoproj/argo-workflows/commit/206451f066924abf3b4b6756606234150bf10fc9) Fix influxdb-ci.yml example
 * [da582a51](https://github.com/argoproj/argo-workflows/commit/da582a5194056a08d5eef95c2441b562cde08740) Avoid nil pointer for 2.0 workflows. (#820)
 * [0f225cef](https://github.com/argoproj/argo-workflows/commit/0f225cef91f4b276e24270a827c37dcd5292a4f0) ClusterRoleBinding was using incorrect service account namespace reference when overriding install namespace (resolves #814)
 * [66ea711a](https://github.com/argoproj/argo-workflows/commit/66ea711a1c7cc805282fd4065e029287f4617d57) Issue #816 - fix updating outboundNodes field of failed step group node (#817)
 * [00ceef6a](https://github.com/argoproj/argo-workflows/commit/00ceef6aa002199186475350b95ebc2d32debf14) install & uninstall commands use --namespace flag (#813)
 * [fe23c2f6](https://github.com/argoproj/argo-workflows/commit/fe23c2f651a61a2d7aa877a86edff9802d7b5b47) Issue #810 - `argo install`does not install argo ui (#811)
 * [28673ed2](https://github.com/argoproj/argo-workflows/commit/28673ed2f85ca39f5d9b136382ea9a87da0ca716) Update release date in change log
 * [05e8a983](https://github.com/argoproj/argo-workflows/commit/05e8a98386ccc73a02f39357f6faed69f7d11a17) Update change log for 2.1.0-beta1 release
 * [bf38b6b5](https://github.com/argoproj/argo-workflows/commit/bf38b6b509ae3fb123e47da2570906d0262ccf67) Use socket type for hostPath to mount docker.sock (#804) (#809)
 * [37680ef2](https://github.com/argoproj/argo-workflows/commit/37680ef26585f412930694cc809d9870d655bd13) Minimal shell completion support (#807)
 * [c83ad24a](https://github.com/argoproj/argo-workflows/commit/c83ad24a6fb5eb7054af16ae2c4f95de8df3965b) Omit empty status fields. (#806)
 * [d7291a3e](https://github.com/argoproj/argo-workflows/commit/d7291a3ee3b5375f8a079b60c568380e1bb91de9) Issue #660 - Support rendering logs from all steps using 'argo logs' command (#792)
 * [7d3f1e83](https://github.com/argoproj/argo-workflows/commit/7d3f1e83d3e08b13eb705ddd74244ea29e019c1a) Minor edits to README
 * [7a4c9c1f](https://github.com/argoproj/argo-workflows/commit/7a4c9c1f9c4fbd5282c57011c0bdcd48fe10137b) Added a review to README
 * [383276f3](https://github.com/argoproj/argo-workflows/commit/383276f300e666bf133a0355f2da493997ddd6cc) Inlined LICENSE file. Renamed old license to COPYRIGHT
 * [91d0f47f](https://github.com/argoproj/argo-workflows/commit/91d0f47fec82c7cef156ac05287622adc0b0a53b) Build argo cli image (#800)
 * [3b2c426e](https://github.com/argoproj/argo-workflows/commit/3b2c426ee5ba6249fec0d0a59353bfe77cb0966c) Add ability to pass pod annotations and labels at the template level (#798)
 * [d8be0287](https://github.com/argoproj/argo-workflows/commit/d8be0287f04f1d0d3bdee60243e0742594009bc8) Add ability to use IAM role from EC2 instance for AWS S3 credentials
 * [624f0f48](https://github.com/argoproj/argo-workflows/commit/624f0f48306183da33e2ef3aecf9566bb0ad8ad3) Update CHANGELOG.md for v2.1.0-beta1 release
 * [e96a09a3](https://github.com/argoproj/argo-workflows/commit/e96a09a3911f039038ea3038bed3a8cd8d63e269) Allow spec.arguments to be not supplied during linting. Global parameters were not referencable from artifact arguments (resolves #791)
 * [018e663a](https://github.com/argoproj/argo-workflows/commit/018e663a53aeda35149ec9b8de28f26391eb688e) Fix for https://github.com/argoproj/argo/issues/739 Nested stepgroups render correctly (#790)
 * [5c5b35ba](https://github.com/argoproj/argo-workflows/commit/5c5b35ba271fb48c38bf65e386e3d8b574f49373) Fix install issue where service account was not being created
 * [88e9e5ec](https://github.com/argoproj/argo-workflows/commit/88e9e5ecb5fc9e5215033a11abf6f6ddf50db253) packr needs to run compiled in order to cross compile darwin binaries
 * [dcdf9acf](https://github.com/argoproj/argo-workflows/commit/dcdf9acf9c7c3f58b3adfbf1994a5d3e7574dd9c) Fix install tests and build failure
 * [06c0d324](https://github.com/argoproj/argo-workflows/commit/06c0d324bf93a037010186fe54e40590ea39d92c) Rewrite the installer such that manifests are maintainable
 * [a45bf1b7](https://github.com/argoproj/argo-workflows/commit/a45bf1b7558b3eb60ec65d02c166c306e7797a79) Introduce support for exported global output parameters and artifacts
 * [60c48a9a](https://github.com/argoproj/argo-workflows/commit/60c48a9aa4b4dbf4c229e273faa945e0f5982539) Introduce `argo retry` to retry a failed workflow with the same name (resolves #762) onExit and related nodes should never be executed during resubmit/retry (resolves #780)
 * [90c08bff](https://github.com/argoproj/argo-workflows/commit/90c08bffc1b12b4c7941daccbf417772f17e3704) Refactor command structure
 * [101509d6](https://github.com/argoproj/argo-workflows/commit/101509d6b5ebeb957bb7ad6e819a961a26812a0e) Abstract the container runtime as an interface to support mocking and future runtimes Trim a trailing newline from path-based output parameters (resolves #758)
 * [a3441d38](https://github.com/argoproj/argo-workflows/commit/a3441d38b9be1f75506ab91dfbac7d6546d2b900) Add ability to reference global parameters in spec level fields (resolves #749)
 * [cd73a9ce](https://github.com/argoproj/argo-workflows/commit/cd73a9ce18aae35beee5012c68f553ab0c46030d) Fix template.parallelism limiting parallelism of entire workflow (resolves #772) Refactor operator to make template execution method signatures consistent
 * [7d7b74fa](https://github.com/argoproj/argo-workflows/commit/7d7b74fa8a62c43f8891a9af1dcae71f6efdc7e0) Make {{pod.name}} available as a parameter in pod templates (resolves #744)
 * [3cf4bb13](https://github.com/argoproj/argo-workflows/commit/3cf4bb136a9857ea17921a2ec6cfd95b4b95a0d7) parse the artifactory URL before appending the artifact to the path (#774)
 * [ea1257f7](https://github.com/argoproj/argo-workflows/commit/ea1257f717676997f0efcac9086ed348613a28c7) examples: use alpine python image
 * [2114078c](https://github.com/argoproj/argo-workflows/commit/2114078c533db0ab34b2f76fe481f03eba046cc1) fix typo
 * [9f605589](https://github.com/argoproj/argo-workflows/commit/9f6055899fff0b3161bb573159b13fd337e2e35f) Fix retry-container-to-completion example
 * [07422f26](https://github.com/argoproj/argo-workflows/commit/07422f264ed62a428622505e1880d2d5787d50ae) Update CHANGELOG release date. Remove ui-image from release target
 * [5d60d073](https://github.com/argoproj/argo-workflows/commit/5d60d073a1a6c2151ca3a07c15dd2580c92fc11d) Fix make release target
 * [a013fb38](https://github.com/argoproj/argo-workflows/commit/a013fb381b30ecb513def88a0ec3160bdc18a5d1) Fix inability to override LDFLAGS when env variables were supplied to make
 * [f63e552b](https://github.com/argoproj/argo-workflows/commit/f63e552b1c8e191689cfb73751654782de94445c) Minor spell fix for parallelism
 * [88d2ff3a](https://github.com/argoproj/argo-workflows/commit/88d2ff3a7175b0667351d0be611b97c2ebee908c) Add UI changes description for 2.1.0-alpha1 release (#761)
 * [ce4edb8d](https://github.com/argoproj/argo-workflows/commit/ce4edb8dfab89e9ff234b12d3ab4996183a095da) Add contributor credits
 * [cc8f35b6](https://github.com/argoproj/argo-workflows/commit/cc8f35b636558f98cd2bd885142aa1f8fd94cb75) Add note about region discovery.
 * [9c691a7c](https://github.com/argoproj/argo-workflows/commit/9c691a7c88904a50427349b698039ff90b1cf83b) Trim spaces from aws keys
 * [17e24481](https://github.com/argoproj/argo-workflows/commit/17e24481d8b3d8416f3590bb11bbee85123c1eb5) add keyPrefix option to ARTIFACT_REPO.md
 * [57a568bf](https://github.com/argoproj/argo-workflows/commit/57a568bfddc42528cb75580501d0b65264318424) Issue #747 - Support --instanceId parameter in submit a workflow (#748)
 * [81a6cd36](https://github.com/argoproj/argo-workflows/commit/81a6cd3653d1f0708bff4207e8df90c3dec4889a) Move UI code to separate repository (#742)
 * [10c7de57](https://github.com/argoproj/argo-workflows/commit/10c7de57478e13f6a11c77bcdf3ac3b0ae78fda7) Fix rbac resource versions in install
 * [2756e83d](https://github.com/argoproj/argo-workflows/commit/2756e83d7a38bd7307d15ef0328ebc1cf7f40cae) Support workflow pod tolerations
 * [9bdab63f](https://github.com/argoproj/argo-workflows/commit/9bdab63f451a2fff04cd58b55ecb9518f937e512) Add workflow.namespace to global parameters
 * [8bf7a1ad](https://github.com/argoproj/argo-workflows/commit/8bf7a1ad3fde2e24f14a79294dd47cb5dae080b1) Statically link argo linux binary (resolves #735)
 * [813cf8ed](https://github.com/argoproj/argo-workflows/commit/813cf8ed26e2f894b0457ee67cbb8d53e86c32c5) Add NodeStatus.DisplayName to remove CLI/UI guesswork from displaying node names (resolves #731)
 * [e783ccbd](https://github.com/argoproj/argo-workflows/commit/e783ccbd30d1e11e3dcec1912b59c76e738a9d79) Rename some internal template type names for consistency
 * [19dd406c](https://github.com/argoproj/argo-workflows/commit/19dd406cf040041ad15ce1867167902954f0f1d5) Introduce suspend templates for suspending a workflow at a predetermined step (resolves #702). Make suspend part of the workflow spec instead of infering parallism in status.
 * [d6489e12](https://github.com/argoproj/argo-workflows/commit/d6489e12f5af8bbb372bfe077a01972235f219d3) Rename pause to suspend
 * [f1e2f63d](https://github.com/argoproj/argo-workflows/commit/f1e2f63dbdf30895a7829337dcec6bcf4b54b5da) Change definition of WorkflowStep.Item to a struct instead of interface{} (resolves #723) Add better withItems unit testing and validation
 * [cd18afae](https://github.com/argoproj/argo-workflows/commit/cd18afae4932fd29b614a1b399edb84184d7a053) Missed handling of a error during workflow resubmission
 * [a7ca59be](https://github.com/argoproj/argo-workflows/commit/a7ca59be870397271fabf5dba7cdfca7d79a934f) Support resubmission of failed workflows with ability to re-use successful steps (resolves #694)
 * [76b41877](https://github.com/argoproj/argo-workflows/commit/76b41877c8a90b2e5529f9fe305f8ebdbcb72377) Include inputs as part of NodeStatus (resolves #730)
 * [ba683c1b](https://github.com/argoproj/argo-workflows/commit/ba683c1b916fd47bf21028cd1338ef8a7b4b7601) Support for manual pausing and resuming of workflows via Argo CLI (resolves #729)
 * [5a806f93](https://github.com/argoproj/argo-workflows/commit/5a806f93a398faefc276d958d476e77c12989a72) Add DAG gif for argo wiki (#728)
 * [62a3fba1](https://github.com/argoproj/argo-workflows/commit/62a3fba106be6a331ba234614c24562e620154c0) Implement support for DAG templates to have output parameters/artifacts
 * [989e8ed2](https://github.com/argoproj/argo-workflows/commit/989e8ed2c9e87ae4cc33df832f8ae4fb87c69fa7) Support parameter and artifact passing between DAG tasks. Improved template validation
 * [03d409a3](https://github.com/argoproj/argo-workflows/commit/03d409a3ac62a9e631c1f195b53fff70c8dfab7b) Switch back to Updating CRDs (from Patch) to enable better unit testing
 * [2da685d9](https://github.com/argoproj/argo-workflows/commit/2da685d93ff234f79689f40b3123667de81acce3) Fixed typos in examples/README.md
 * [6cf94b1b](https://github.com/argoproj/argo-workflows/commit/6cf94b1bf4d95c1e76a15c7ef36553cc301cf27d) Added output parameter example to examples/README.md
 * [0517096c](https://github.com/argoproj/argo-workflows/commit/0517096c32cd4f2443ae4208012c6110fbd07ab6) Add templateName as part of NodeStatus for UI consumption Simplify and centralize parallelism check into executeTemplate() Improved template validation
 * [deae4c65](https://github.com/argoproj/argo-workflows/commit/deae4c659b3c38f78fe5c8537319ea954fcfa54d) Add parallelism control at the steps template level
 * [c788484e](https://github.com/argoproj/argo-workflows/commit/c788484e1cbbe158c2d7cdddd30b1a8242e2c30c) Remove hard-wired executor limits and make it configurable in the controller (resolves #724)
 * [f27c7ffd](https://github.com/argoproj/argo-workflows/commit/f27c7ffd4e9bed1ddbbcb0e660854f6b2ce2daac) Fix linting issues (ineffassign, errcheck)
 * [98a44c99](https://github.com/argoproj/argo-workflows/commit/98a44c99c2515f2295327ae9572732586ddc3d7b) Embed container type into the script template instead of cherry-picking fields (resolves #711)
 * [c0a8f949](https://github.com/argoproj/argo-workflows/commit/c0a8f949b5ce9048fbc6f9fcc89876c8ad32c85c) Bump VERSION to 2.1.0
 * [207de824](https://github.com/argoproj/argo-workflows/commit/207de82474a3c98411072345f542ebee4d8e7208) Add parallism field to limit concurrent pod execution at a workflow level (issue #666)
 * [460c9555](https://github.com/argoproj/argo-workflows/commit/460c9555b760aa9405e959a96b6c8cf339096573) Do not initialize DAG task nodes if they did not execute
 * [13a60936](https://github.com/argoproj/argo-workflows/commit/13a60936ded42563617ad3d572c0c84d95b6c638) Merge branch 'feature-dag'
 * [931d7723](https://github.com/argoproj/argo-workflows/commit/931d7723cc42b3fc6d937b737735c9985cf91958) Update docs to refer to v2.0.0
 * [0978b9c6](https://github.com/argoproj/argo-workflows/commit/0978b9c61cb7435d31ef8d252b80e03708a70adc) Support setting UI base Url  (#722)
 * [b75cd98f](https://github.com/argoproj/argo-workflows/commit/b75cd98f6c038481ec3d2253e6404952bcaf4bd5) updated argo-user slack link
 * [b3598d84](https://github.com/argoproj/argo-workflows/commit/b3598d845c4cdb9ac7c4ae5eff5024ecd3fc5fd6) Add examples as functional and expected failure e2e tests
 * [83966e60](https://github.com/argoproj/argo-workflows/commit/83966e6095e2468368b0929613e7371074ee972b) Fix regression where executor did not annotate errors correctly
 * [751fd270](https://github.com/argoproj/argo-workflows/commit/751fd27024d9f3bfc40051d2ca694b25a42307ea) Update UI references to v2.0.0. Update changelog
 * [75caa877](https://github.com/argoproj/argo-workflows/commit/75caa877bc08184cad6dd34366b2b9f8b3dccc38) Initial work for dag based cli for everything. get now works (#714)
 * [8420deb3](https://github.com/argoproj/argo-workflows/commit/8420deb30a48839a097d3f5cd089e4b493b5e751) Skipped steps were being re-initialized causing a controller panic
 * [491ed08f](https://github.com/argoproj/argo-workflows/commit/491ed08ffe2f8430fcf35bf36e6dd16707eb5a0a) Check-in the OpenAPI spec. Automate generation as part of `make update-codegen`
 * [8b7e2e24](https://github.com/argoproj/argo-workflows/commit/8b7e2e24e8cf7ae6b701f08b0702ac045e0336f8) Check-in the OpenAPI spec. Automate generation as part of `make update-codegen`
 * [17241165](https://github.com/argoproj/argo-workflows/commit/17241165d004329e14bfc948759b38d4e17e5724) Merge branch 'master' into feature-dag
 * [563bda75](https://github.com/argoproj/argo-workflows/commit/563bda756732802caeaa516fd0c493c6e07f6cf9) Fix update-openapigen.sh script to presume bash. Tweak documentation
 * [5b9a602b](https://github.com/argoproj/argo-workflows/commit/5b9a602b4a763ac633f7ede86f13253451855462) Add documentation to types. Add program to generate OpenAPI spec
 * [42726910](https://github.com/argoproj/argo-workflows/commit/4272691035e0588bbd301449c122ee2851e3c87f) Fix retry in dag branch (#709)
 * [97204e64](https://github.com/argoproj/argo-workflows/commit/97204e64c5823a1563a87bd62f56613c0434a8f8) Merge branch 'master' into feature-dag
 * [d929e79f](https://github.com/argoproj/argo-workflows/commit/d929e79f623017a923d1c4e120c363e08fe7a64a) Generate OpenAPI models for the workflow spec (issue #707)
 * [1d5afee6](https://github.com/argoproj/argo-workflows/commit/1d5afee6ea48743bb854e69ffa333f361e52e289) Shortened url
 * [617d848d](https://github.com/argoproj/argo-workflows/commit/617d848da27d0035c20f21f3f6bddbe0e04550db) Added news to README
 * [ae36b22b](https://github.com/argoproj/argo-workflows/commit/ae36b22b6d0d0ce8c230aedcce0814489162ae5b) Fix typo s/Customer/Custom/ (#704)
 * [5a589fcd](https://github.com/argoproj/argo-workflows/commit/5a589fcd932116720411d53aeb6454e297456e06) Add ability to specify imagePullSecrets in the workflow.spec (resolves #699)
 * [2f77bc1e](https://github.com/argoproj/argo-workflows/commit/2f77bc1ed00042388d0492cfd480d7c22599112c) Add ability to specify affinity rules at both the workflow and template level (resolves #701)
 * [c2dd9b63](https://github.com/argoproj/argo-workflows/commit/c2dd9b635657273c3974fc358fcdf797c821ac92) Fix unit test breakages
 * [d38324b4](https://github.com/argoproj/argo-workflows/commit/d38324b46100e6ba07ad1c8ffc957c257aac41d7) Add boundaryID field in NodeStatus to group nodes by template boundaries
 * [639ad1e1](https://github.com/argoproj/argo-workflows/commit/639ad1e15312da5efa88fd62a0f3aced2ac17c52) Introduce Type field in NodeStatus to to assist with visualization
 * [17601c61](https://github.com/argoproj/argo-workflows/commit/17601c618a463edc1d971d462eec5e235835682d) Merge branch 'master' into feature-dag
 * [fdafbe27](https://github.com/argoproj/argo-workflows/commit/fdafbe27e5e2f4f2d58913328ae22db9a6c363b4) Sidecars unable to reference volume claim templates (resolves #697)
 * [0b0b52c3](https://github.com/argoproj/argo-workflows/commit/0b0b52c3b45cbe5ac62da7b26b30d19fc1f9eb3e) Referencing output artifacts from a container with retries was not functioning (resolves #698)
 * [9597f82c](https://github.com/argoproj/argo-workflows/commit/9597f82cd7a8b65cb03e4dfaa3023dcf20619b9d) Initial support for DAG based workflows (#693)
 * [bf2b376a](https://github.com/argoproj/argo-workflows/commit/bf2b376a142ed4fdf70ba4f3702533e7b75fc6b2) Update doc references to point to v2.0.0-beta1. Fix secrets example

### Contributors

 * Adam Pearse
 * Alexander Matyushentsev
 * Andrea Kao
 * Dan Bode
 * David Kale
 * Divya Vavili
 * Dmitry Monakhov
 * Edward Lee
 * Javier Castellanos
 * Jesse Dubay
 * Jesse Suen
 * Johannes 'fish' Ziemke
 * Lukasz Lempart
 * Matt Hillsdon
 * Mukulikak
 * Sean Fitzgerald
 * Sebastien Doido
 * Yang Pan
 * dougsc
 * gaganapplatix

## v2.0.0-beta1 (2018-01-18)

 * [549870c1](https://github.com/argoproj/argo-workflows/commit/549870c1ee08138b20b8a4b0c026569cf1e6c19a) Fix argo-ui download links to point to v2.0.0-beta1
 * [a202049d](https://github.com/argoproj/argo-workflows/commit/a202049d327c64e282a37d7598bddc1faa1a3c1a) Update CHANGELOG for v2.0.0-beta1
 * [a3739035](https://github.com/argoproj/argo-workflows/commit/a3739035f8e1f517721489fc53b58a8e27a575e1) Remove dind requirement from argo-ci test steps
 * [1bdd0c03](https://github.com/argoproj/argo-workflows/commit/1bdd0c03dbb9d82ad841ca19be6e1ea93aeb82f7) Include completed pods when attempting to reconcile deleted pods Switch back to Patch (from Update) for persisting workflow changes
 * [a4a43892](https://github.com/argoproj/argo-workflows/commit/a4a4389219cbe84e3bc7b3731cdfccb9ee5f5730) Sleep 1s after persisting workflow to give informer cache a chance to sync (resolves #686)
 * [5bf49531](https://github.com/argoproj/argo-workflows/commit/5bf49531f99ef9d8b8aefeac26a4a3fa0177e70d) Updated demo.md with link to ARTIFACT_REPO.md
 * [863d547a](https://github.com/argoproj/argo-workflows/commit/863d547a1a2a146a898c06c835187e0595af5689) Rely on controller generated timestamps for node.StartedAt instad of pod.CreationTimestamp
 * [672542d1](https://github.com/argoproj/argo-workflows/commit/672542d1f08c206f89f8747e9b14b675cdd77446) Re-apply workflow changes and reattempt update on resource conflicts. Make completed pod labeling asynchronous
 * [81bd6d3d](https://github.com/argoproj/argo-workflows/commit/81bd6d3d46d2fd7ea57aa095ae134116cfca90f2) Resource state retry (#690)
 * [44dba889](https://github.com/argoproj/argo-workflows/commit/44dba889cb743552557fcd7453ee81a89875142d) Tune controller to 20 QPS, 30 Burst, 8 wf workers, 8 pod workers
 * [178b9d37](https://github.com/argoproj/argo-workflows/commit/178b9d37cc452af214df7c9c41522124c117e7a3) Show running/completed pod counts in `argo list -o wide`
 * [0c565f5f](https://github.com/argoproj/argo-workflows/commit/0c565f5f5e9f69244e9828ced7c3916ac605f460) Switch to Updating workflow resources instead of Patching (resolves #686)
 * [a571f592](https://github.com/argoproj/argo-workflows/commit/a571f592fa131771b8d71126fc27809e24462cfe) Ensure sidecars get killed unequivocally. Final argoexec stats were not getting printed
 * [a0b2d78c](https://github.com/argoproj/argo-workflows/commit/a0b2d78c869f277c20c4cd3ba18b8d2688674e54) Show duration by default in `argo get`. --since flag should always include Running
 * [10110313](https://github.com/argoproj/argo-workflows/commit/101103136287b8ee16a7afda94cc6ff59be07ef6) Executor hardening: add retries and memoization for executor k8s API calls Recover from unexpected panics and annotate the error.
 * [f2b8f248](https://github.com/argoproj/argo-workflows/commit/f2b8f248ab8d483e0ba41a287611393500c7b507) Regenerate deepcopy code after type changes for raw input artifacts
 * [322e0e3a](https://github.com/argoproj/argo-workflows/commit/322e0e3aa3cb2e650f3ad4b7ff9157f71a92e8b4) renamed file as per review comment
 * [0a386cca](https://github.com/argoproj/argo-workflows/commit/0a386ccaf705a1abe1f9239adc966fceb7a808ae) changes from the review - renamed "contents" to "data" - lint issue
 * [d9ebbdc1](https://github.com/argoproj/argo-workflows/commit/d9ebbdc1b31721c8095d3c5426c1c811054a94a7) support for raw input as artifact
 * [a1f821d5](https://github.com/argoproj/argo-workflows/commit/a1f821d589d47ca5b12b94ad09306a706a43d150) Introduce communication channel from workflow-controller to executor through pod annotations
 * [b324f9f5](https://github.com/argoproj/argo-workflows/commit/b324f9f52109b9aa29bc89d63810be6e421eb54f) Artifactory repository was not using correct casing for repoURL field
 * [3d45d25a](https://github.com/argoproj/argo-workflows/commit/3d45d25ac497a09fa291d20f867a75f59b6abf92) Add `argo list --since` to filter workflows newer than a relative duration
 * [cc2efdec](https://github.com/argoproj/argo-workflows/commit/cc2efdec368c2f133c076a9eda9065f64762a9fa) Add ability to set loglevel of controller via CLI flag
 * [60c124e5](https://github.com/argoproj/argo-workflows/commit/60c124e5dddb6ebfee6300d36f6a3877838ec17c) Remove hack.go and use dep to install code-generators
 * [d14755a7](https://github.com/argoproj/argo-workflows/commit/d14755a7c5f583c1f3c8c762ae8628e780f566cf) `argo list` was not handling the default case correctly
 * [472f5604](https://github.com/argoproj/argo-workflows/commit/472f5604e27ca6310e016f846c97fda5d7bca9dd) Improvements to `argo list` * sort workflows by running vs. completed, then by finished time * add --running, --completed, --status XXX filters * add -o wide option to show parameters and -o name to show only the names
 * [b063f938](https://github.com/argoproj/argo-workflows/commit/b063f938f34f650333df6ec5a2e6a325a5b45299) Use minimal ClusterRoles for workflow-controller and argo-ui deployments
 * [21bc2bd0](https://github.com/argoproj/argo-workflows/commit/21bc2bd07ebbfb478c87032e2ece9939ea436030) Added link to configuring artifact repo from main README
 * [b54bc067](https://github.com/argoproj/argo-workflows/commit/b54bc067bda02f95937774fb3345dc2010d3efc6) Added link to configuring artifact repo from main README
 * [58ec5169](https://github.com/argoproj/argo-workflows/commit/58ec51699534e73d82c3f44027326b438cf5c063) Updated ARTIFACT_REPO.md
 * [1057d087](https://github.com/argoproj/argo-workflows/commit/1057d087838bcbdbffc70367e0fc02778907c9af) Added detailed instructions on configuring AWS and GCP artifact rpos
 * [b0a7f0da](https://github.com/argoproj/argo-workflows/commit/b0a7f0da85fabad34814ab129eaba43862a1d2dd) Issue 680 - Argo UI is failing to render workflow which has not been picked up by workflow controller (#681)
 * [e91c227a](https://github.com/argoproj/argo-workflows/commit/e91c227acc1f86b7e341aaac534930f9b529cd89) Document and clarify artifact passing (#676)
 * [290f6799](https://github.com/argoproj/argo-workflows/commit/290f6799752ef602b27c193212495e27f40dd687) Allow containers to be retried. (#661)
 * [80f9b1b6](https://github.com/argoproj/argo-workflows/commit/80f9b1b636704ebad6ebb8df97c5e81dc4f815f9) Improve the error message when insufficent RBAC privileges is detected (resolves #659)
 * [3cf67df4](https://github.com/argoproj/argo-workflows/commit/3cf67df422f34257296d2de09d2ca3c8c87abf84) Regenerate autogenerated code after changes to types
 * [baf37052](https://github.com/argoproj/argo-workflows/commit/baf37052976458401a6c0e44d06f30dc8d819680) Add support for resource template outputs. Remove output.parameters.path in favor of valueFrom
 * [dc1256c2](https://github.com/argoproj/argo-workflows/commit/dc1256c2034f0add4bef3f82ce1a71b454d4eef5) Fix expected file name for issue template
 * [a492ad14](https://github.com/argoproj/argo-workflows/commit/a492ad14177eb43cdd6c2a017c9aec87183682ed) Add a GitHub issues template
 * [55be93a6](https://github.com/argoproj/argo-workflows/commit/55be93a68d8991f76a31adaf49f711436a35a9d0) Add a --dry-run option to `argo install`. Remove CRD creation from controller startup
 * [fddc052d](https://github.com/argoproj/argo-workflows/commit/fddc052df8a3478aede67057f2b06938c2a6a7a4) Fix README.md to contain influxdb-client in the example (#669)
 * [67236a59](https://github.com/argoproj/argo-workflows/commit/67236a5940231f7b9dc2ca2f4cb4cb70b7c18d45) Update getting started doc to use `brew install` and better instructions for RBAC clusters (resolves #654, #530)
 * [5ac19753](https://github.com/argoproj/argo-workflows/commit/5ac19753846566d0069b76e3e6c6dd03f0e6950c) Support rendering retry steps (#670)
 * [3cca0984](https://github.com/argoproj/argo-workflows/commit/3cca0984c169ea59e8e2758a04550320b1981875) OpenID Connect auth support (#663)
 * [c222cb53](https://github.com/argoproj/argo-workflows/commit/c222cb53a168f9bd40b7731d0b2f70db977990c2) Clarify where the Minio secret comes from.
 * [a78e2e8d](https://github.com/argoproj/argo-workflows/commit/a78e2e8d551d6afad2e0fbce7a9f0a1bd023c11b) Remove parallel steps that use volumes.
 * [35517385](https://github.com/argoproj/argo-workflows/commit/355173857f98a9a9704ab23235b3186bde8092b9) Prevent a potential k8s scheduler panic from incomplete setting of pod ownership reference (resolves #656)
 * [1a8bc26d](https://github.com/argoproj/argo-workflows/commit/1a8bc26d40597f2f0475aa9197a6b3912c5bbb56) Updated README
 * [9721fca0](https://github.com/argoproj/argo-workflows/commit/9721fca0e1ae9d1d57aa8d1872450ce8ee7487e2) Updated README
 * [e3177606](https://github.com/argoproj/argo-workflows/commit/e3177606105a936da7eba29924fa49ad497703c9) Fix typos in READMEs
 * [555d50b0](https://github.com/argoproj/argo-workflows/commit/555d50b0ebeef1c753394de974dad2e0d4a5b787) Simplify some getting started instructions. Correct some usages of container resources field
 * [4abc9c40](https://github.com/argoproj/argo-workflows/commit/4abc9c40e7656a5783620e41b33e4ed3bb7249e2) Updated READMEs
 * [a0add24f](https://github.com/argoproj/argo-workflows/commit/a0add24f9778789473b2b097fb31a56ae11bfce9) Switch to k8s-codegen generated workflow client and informer
 * [9b08b6e9](https://github.com/argoproj/argo-workflows/commit/9b08b6e997633d5f2e94392f000079cbe93ee023) Added link for argoproj slack channel
 * [682bbdc0](https://github.com/argoproj/argo-workflows/commit/682bbdc09b66698090d309e91b5caf4483931e34) Update references to point to latest argo release

### Contributors

 * Alexander Matyushentsev
 * Ed Lee
 * Jesse Suen
 * Matt Hillsdon
 * Rhys Parry
 * Sandeep Bhojwani
 * Shri Javadekar
 * gaganapplatix

## v2.0.0-alpha3 (2018-01-02)

 * [940dd56d](https://github.com/argoproj/argo-workflows/commit/940dd56d98c75eb93da3b5de598882754cb74fc7) Fix artifactory unit test and linting issues
 * [e7ba2b44](https://github.com/argoproj/argo-workflows/commit/e7ba2b44114fca8a3cb2b8635dc2fdfeaa440d9e) Update help page links (#651)
 * [53dac4c7](https://github.com/argoproj/argo-workflows/commit/53dac4c74933c333124a0cb1d8cf6c9255f9199d) Add artifactory and UI fixes to 2.0.0-alpha3 CHANGELOG
 * [4b4eff43](https://github.com/argoproj/argo-workflows/commit/4b4eff43f20ed678d34efe567a4d61d1364d7124) Allow disabling web console feature (#649)
 * [90b7f2e6](https://github.com/argoproj/argo-workflows/commit/90b7f2e67dddebba1678e215bde75d68867b4469) Added support for artifactory
 * [849e916e](https://github.com/argoproj/argo-workflows/commit/849e916e5bf98f320f1a65b12ffe246d9ebbb6f6) Adjusted styles for logs stream (#614)
 * [a8a96030](https://github.com/argoproj/argo-workflows/commit/a8a960303423cde2e511d4af9c2c8ae834076b21) Update CHANGELOG for 2.0.0-alpha3
 * [e7c7678c](https://github.com/argoproj/argo-workflows/commit/e7c7678cc605285e5b3224c757e5e4be57ab4d5c) Fix issue preventing ability to pass JSON as a command line param (resolves #646)
 * [7f5e2b96](https://github.com/argoproj/argo-workflows/commit/7f5e2b96bd96e0bccf4778383aa9b94a1768e9c0) Add validation checks for volumeMount/artifact path collision and activeDeadlineSeconds (#620)
 * [dc4a9463](https://github.com/argoproj/argo-workflows/commit/dc4a94633c4d00d78a7ea53272e425962de405ba) Add the ability to specify the service account used by pods in the workflow (resolves #634) Also add argo CLI support for supplying/overriding spec.serviceAccountName from command line.
 * [16f7000a](https://github.com/argoproj/argo-workflows/commit/16f7000aa77b2759fa0a65d6e42456bcb660f824) Workflow operator will recover from unexpected panics and mark the workflow with error (resolves #633)
 * [18dca7fe](https://github.com/argoproj/argo-workflows/commit/18dca7fe21d57e6a5415c53bfdb87a889ac32456) Issue #629 - Add namespace to workflow list and workflow details page (#639)
 * [e656bace](https://github.com/argoproj/argo-workflows/commit/e656bace75aaa859f04121f2c1d95631b462fe62) Issue #637 -  Implement Workflow list and workflow details page live update (#638)
 * [1503ce3a](https://github.com/argoproj/argo-workflows/commit/1503ce3aee40eba741819a1403847df4bbcb7b23) Issue #636 - Upgrade to ui-lib 2.0.3 to fix xterm incompatibility (#642)
 * [f9170e8a](https://github.com/argoproj/argo-workflows/commit/f9170e8abb7121b0d0cbc3e4c07b9bdc2224fb76) Remove manifest-passing.yaml example now that we have resource templates
 * [25be5fd6](https://github.com/argoproj/argo-workflows/commit/25be5fd6368bac3fde8e4392b3cb9d4159983a1a) Implementation for resource templates and resource success/failure conditions
 * [402ad565](https://github.com/argoproj/argo-workflows/commit/402ad565f4a3b95c449ddd4c6dc468947aeb7192) Updated examples/README
 * [8536c7fc](https://github.com/argoproj/argo-workflows/commit/8536c7fc89a0ceb39208efe2076919d0390e3d2e) added secret example to examples/README
 * [e5002b82](https://github.com/argoproj/argo-workflows/commit/e5002b8286af2c1f7ec64953114e1d97c889ca37) Add '--wait' to argo submit.
 * [9646e55f](https://github.com/argoproj/argo-workflows/commit/9646e55f8bb8fbac80d456853aa891c2ae069adb) Installer was not update configmap correctly with new executor image during upgrade
 * [69d72913](https://github.com/argoproj/argo-workflows/commit/69d72913a3a72bbf7b075be847303305b4bef1a5) Support private git repos using secret selector fields in the git artifact (resolves #626)
 * [64e17244](https://github.com/argoproj/argo-workflows/commit/64e17244ef04b9d2aa6abf6f18d4e7ef2d20ff37) Add argo ci workflow (#619)
 * [e8998435](https://github.com/argoproj/argo-workflows/commit/e8998435598e8239d7b77a60cfda43e8f2869b4d) Resolve controller panic when a script template with an input artifact was submitted (resolves #617). Utilize the kubernetes.Interface and fake.Clientset to support unit test mocking. Added a unit test to reproduce the panic. Add an e2e test to verify functionality works.
 * [52075b45](https://github.com/argoproj/argo-workflows/commit/52075b45611783d909609433bb44702888b5db37) Introduce controller instance IDs to support multiple workflow controllers in a cluster (resolves #508)
 * [133a23ce](https://github.com/argoproj/argo-workflows/commit/133a23ce20b4570ded81fac76a430f0399c1eea1) Add ability to timeout a container/script using activeDeadlineSeconds
 * [b5b16e55](https://github.com/argoproj/argo-workflows/commit/b5b16e55260df018cc4de14bf298ce59714b4396) Support for workflow exit handlers
 * [906b3e7c](https://github.com/argoproj/argo-workflows/commit/906b3e7c7cac191f920016362b076a28f18d97c1) Update ROADMAP.md
 * [5047422a](https://github.com/argoproj/argo-workflows/commit/5047422ae71869672c84364d099e1488b29fbbe8) Update CHANGELOG.md
 * [2b6583df](https://github.com/argoproj/argo-workflows/commit/2b6583dfb02911965183ef4b25ed68c867448e10) Add `argo wait` for waiting on workflows to complete. (#618)
 * [cfc9801c](https://github.com/argoproj/argo-workflows/commit/cfc9801c40528b6605823e1f4b4359600b6887df) Add option to print output of submit in json.
 * [c20c0f99](https://github.com/argoproj/argo-workflows/commit/c20c0f9958ceeefd3597120fcb4013d857276076) Comply with semantic versioning. Include build metadata in `argo version` (resolves #594)
 * [bb5ac7db](https://github.com/argoproj/argo-workflows/commit/bb5ac7db52bff613c32b153b82953ec9c73c3b8a) minor change
 * [91845d49](https://github.com/argoproj/argo-workflows/commit/91845d4990ff8fd97bd9404e4b37024be1ee0ba6) Added more documentation
 * [4e8d69f6](https://github.com/argoproj/argo-workflows/commit/4e8d69f630bc0fd107b360ee9ad953ccb0b78f11) fixed install instructions
 * [0557147d](https://github.com/argoproj/argo-workflows/commit/0557147dd4bfeb2688b969293ae858a8391d78ad) Removed empty toolbar (#600)
 * [bb2b29ff](https://github.com/argoproj/argo-workflows/commit/bb2b29ff5e4178e2c8a9dfe666b699d75aa9ab3b) Added limit for number of steps in workflows list (#602)
 * [3f57cc1d](https://github.com/argoproj/argo-workflows/commit/3f57cc1d2ff9c0e7ec40da325c3478a8037a6ac0) fixed typo in examples/README
 * [ebba6031](https://github.com/argoproj/argo-workflows/commit/ebba6031192b0a763bd94b1625a2ff6e242f112e) Updated examples/README.md with how to override entrypoint and parameters
 * [81834db3](https://github.com/argoproj/argo-workflows/commit/81834db3c0bd12758a95e8a5862d6dda6d0dceeb) Example with using an emptyDir volume.
 * [4cd949d3](https://github.com/argoproj/argo-workflows/commit/4cd949d327ddb9d4f4592811c51e07bb53b30ef9) Remove apiserver
 * [6a916ca4](https://github.com/argoproj/argo-workflows/commit/6a916ca447147e4aff364ce032c9db4530d49d11) `argo lint` did not split yaml files. `argo submit` was not ignoring non-workflow manifests
 * [bf7d9979](https://github.com/argoproj/argo-workflows/commit/bf7d997970e967b2b238ce209ce823ea47de01d2) Include `make lint` and `make test` as part of CI
 * [d1639ecf](https://github.com/argoproj/argo-workflows/commit/d1639ecfabf73f73ebe040b832668bd6a7b60d20) Create example workflow using kubernetes secrets (resolves #592)
 * [31c54af4](https://github.com/argoproj/argo-workflows/commit/31c54af4ba4cb2a0db918fadf62cb0b854592ba5) Toolbar and filters on workflows list (#565)
 * [bb4520a6](https://github.com/argoproj/argo-workflows/commit/bb4520a6f65d4e8e765ce4d426befa583721c194) Add and improve the inlined comments in example YAMLs
 * [a0470728](https://github.com/argoproj/argo-workflows/commit/a04707282cdeadf463b22b633fc00dba432f60bf) Fixed typo.
 * [13366e32](https://github.com/argoproj/argo-workflows/commit/13366e32467a34a061435091589c90d04a84facb) Fix some wrong GOPATH assumptions in Makefile. Add `make test` target. Fix unit tests
 * [9f4f1ee7](https://github.com/argoproj/argo-workflows/commit/9f4f1ee75705150a22dc68a3dd16fa90069219ed) Add 'misspell' to linters. Fix misspellings caught by linter
 * [1b918aff](https://github.com/argoproj/argo-workflows/commit/1b918aff29ff8e592247d14c52be06a0537f0734) Address all issues in code caught by golang linting tools (resolves #584)
 * [903326d9](https://github.com/argoproj/argo-workflows/commit/903326d9103fa7dcab37835a9478f58aff51a5d1) Add manifest passing to do kubectl create with dynamic manifests (#588)
 * [b1ec3a3f](https://github.com/argoproj/argo-workflows/commit/b1ec3a3fc90a211f9afdb9090d4396c98ab3f71f) Create the argo-ui service with type ClusterIP as part of installation (resolves #582)
 * [5b6271bc](https://github.com/argoproj/argo-workflows/commit/5b6271bc56b46a82b0ee2bc0784315ffcddeb27f) Add validate names for various workflow specific fields and tests for them (#586)
 * [b6e67131](https://github.com/argoproj/argo-workflows/commit/b6e671318a446f129740ce790f53425d65e436f3) Implementation for allowing access to global parameters in workflow (#571)
 * [c5ac5bfb](https://github.com/argoproj/argo-workflows/commit/c5ac5bfb89274fb5ee85f9cef346b7059b5d7641) Fix error message when key does not exist in secret (resolves #574). Improve s3 example and documentation.
 * [4825c43b](https://github.com/argoproj/argo-workflows/commit/4825c43b3e0c3c54b2313aa54e69520ed1b8a38d) Increate UI build memory limit (#580)
 * [87a20c6b](https://github.com/argoproj/argo-workflows/commit/87a20c6bce9a6bfe2a88edc581746ff5f7f006fc) Update input-artifacts-s3.yaml example to explain concepts and usage better
 * [c16a9c87](https://github.com/argoproj/argo-workflows/commit/c16a9c87102fd5b66406737720204e5f17af0fd1) Rahuldhide patch 2 (#579)
 * [f5d0e340](https://github.com/argoproj/argo-workflows/commit/f5d0e340b3626658b435dd2ddd937e97af7676b2) Issue #549 - Prepare argo v1 build config (#575)
 * [3b3a4c87](https://github.com/argoproj/argo-workflows/commit/3b3a4c87bd3138961c948f869e2c5b7c932c8847) Argo logo
 * [d1967443](https://github.com/argoproj/argo-workflows/commit/d1967443a4943f685f6cb1649480765050bdcdaa) Skip e2e tests if Kubeconfig is not provided.
 * [1ec231b6](https://github.com/argoproj/argo-workflows/commit/1ec231b69a1a7d985d1d587980c34588019b04aa) Create separate namespaces for tests.
 * [5ea20d7e](https://github.com/argoproj/argo-workflows/commit/5ea20d7eb5b9193c19f7c875c8fb2f4af8f68ef3) Add a deadline for workflow operation to prevent workqueue starvation and to enable state resync (#531) Tested with 6 x 1000 pod workflows.
 * [346bafe6](https://github.com/argoproj/argo-workflows/commit/346bafe636281bca94695b285767f41ae71e6a69) Multiple scalability improvements to controller (resolves #531)
 * [bbc56b59](https://github.com/argoproj/argo-workflows/commit/bbc56b59e2ff9635244bcb091e92e257a508d147) Improve argo ui build performance and reduce image size (#572)
 * [cdb1ce82](https://github.com/argoproj/argo-workflows/commit/cdb1ce82bce9b103e433981d94bd911b0769350d) Upgrade ui-lib (#556)
 * [0605ad7b](https://github.com/argoproj/argo-workflows/commit/0605ad7b33fc4f9c0bbff79adf1d509d3b072703) Adjusted tabs content size to see horizontal and vertical scrolls. (#569)
 * [a3316236](https://github.com/argoproj/argo-workflows/commit/a331623697e76a5e3497257e28fabe1995852339) Fix rendering 'Error' node status (#564)
 * [8c3a7a93](https://github.com/argoproj/argo-workflows/commit/8c3a7a9393d619951a676324810d482d28dfe015) Issue #548  - UI terminal window  (#563)
 * [5ec6cc85](https://github.com/argoproj/argo-workflows/commit/5ec6cc85aab63ea2277ce621d5de5b59a510d462) Implement API to ssh into pod (#561)
 * [beeb65dd](https://github.com/argoproj/argo-workflows/commit/beeb65ddcb7d2b5f8286f7881af1f5c00535161e) Don't mess the controller's arguments.
 * [01f5db5a](https://github.com/argoproj/argo-workflows/commit/01f5db5a0c3dc48541577b9d8b1d815399728070) Parameterize Install() and related methods.
 * [85a2e271](https://github.com/argoproj/argo-workflows/commit/85a2e2711beba8f2c891af396a3cc886c7b37542) Fix tests.
 * [56f666e1](https://github.com/argoproj/argo-workflows/commit/56f666e1bf69a7f5d8191637e8c7f384b91d98d0) Basic E2e tests.
 * [9eafb9dd](https://github.com/argoproj/argo-workflows/commit/9eafb9dd59166e76804b71c8df19fdca453cdd28) Issue #547 - Support filtering by status in API GET /workflows (#550)
 * [37f41eb7](https://github.com/argoproj/argo-workflows/commit/37f41eb7bf366cfe007d3ecce7b21f003d381e34) Update demo.md
 * [ea8d5c11](https://github.com/argoproj/argo-workflows/commit/ea8d5c113d9245f47fe7b3d3f45e7891aa5f50e8) Update README.md
 * [373f0710](https://github.com/argoproj/argo-workflows/commit/373f07106ab14e3772c94af5cc11f7f1c7099204) Add support for making a no_ui build. Base all build on no_ui build (#553)
 * [ae65c57e](https://github.com/argoproj/argo-workflows/commit/ae65c57e55f92fd8ff1edd099f659e9e97ce59f1) Update demo.md
 * [f6f8334b](https://github.com/argoproj/argo-workflows/commit/f6f8334b2b3ed1f498c19e4de25421f41807f893) V2 style adjustments and small fixes (#544)
 * [12d5b7ca](https://github.com/argoproj/argo-workflows/commit/12d5b7ca48c913e53b74708a35727d523dfa5355) Document argo ui service creation (#545)
 * [3202d4fa](https://github.com/argoproj/argo-workflows/commit/3202d4fac2d5d2d2a3ad1d679c1b753b04aca796) Support all namespaces (#543)
 * [b553c1bd](https://github.com/argoproj/argo-workflows/commit/b553c1bd9a00499915dbe5926194d67c7392b944) Update demo.md to qualify the minio endpoint with the default namespace
 * [4df7617c](https://github.com/argoproj/argo-workflows/commit/4df7617c2e97f2336195d6764259537be648b89b) Fix artifacts downloading (#541)
 * [12732200](https://github.com/argoproj/argo-workflows/commit/12732200fb1ed95608cdc0b14bd0802c524c7fa2) Update demo.md with references to latest release

### Contributors

 * Alexander Matyushentsev
 * Anshuman Bhartiya
 * Ed Lee
 * Javier Castellanos
 * Jesse Suen
 * Rafal
 * Rahul Dhide
 * Sandeep Bhojwani
 * Shri Javadekar
 * Wojciech Kalemba
 * gaganapplatix
 * mukulikak

## v2.0.0-alpha2 (2017-12-04)

 * [0e67b861](https://github.com/argoproj/argo-workflows/commit/0e67b8616444cf637d5b68e58eb6e068b721d34c) Add 'release' make target. Improve CLI help and set version from git tag. Uninstaller for UI
 * [8ab1d2e9](https://github.com/argoproj/argo-workflows/commit/8ab1d2e93ff969a1a01a06dcc3ac4aa04d3514aa) Install argo ui along with argo workflow controller (#540)
 * [f4af881e](https://github.com/argoproj/argo-workflows/commit/f4af881e55cff12888867bca9dff940c1bb16c26) Add make command to build argo ui (#539)
 * [5bb85814](https://github.com/argoproj/argo-workflows/commit/5bb858145e1c603494d8202927197d38b121311a) Add example description in YAML.
 * [fc23fcda](https://github.com/argoproj/argo-workflows/commit/fc23fcdaebc9049748d57ab178517d18eed4af7d) edit example README
 * [8dd294aa](https://github.com/argoproj/argo-workflows/commit/8dd294aa003ee1ffaa70cd7735b7d62c069eeb0f) Add example of GIF processing using ImageMagick
 * [ef8e9d5c](https://github.com/argoproj/argo-workflows/commit/ef8e9d5c234b1f889c4a2accbc9f24d58ce553b9) Implement loader (#537)
 * [2ac37361](https://github.com/argoproj/argo-workflows/commit/2ac37361e6620b37af09cd3e50ecc0fb3fb62a12) Allow specifying CRD version (#536)
 * [15b5542d](https://github.com/argoproj/argo-workflows/commit/15b5542d7cff2b0812830b16bcc5ae490ecc7302) Installer was not using the argo serviceaccount with the workflow-controller deployment. Make progress messages consistent
 * [f1471347](https://github.com/argoproj/argo-workflows/commit/f1471347d96838e0e13e47d0bc7fc04b3018d6f7) Add Yaml viewer (#535)
 * [685a576b](https://github.com/argoproj/argo-workflows/commit/685a576bd28bb269d727a10bf617bd1b08ea4ff0) Fix Gopkg.lock file following rewrite of git history at github.com/minio/go-homedir
 * [01ab3076](https://github.com/argoproj/argo-workflows/commit/01ab3076fe68ef62a9e3cc89b0e367cbdb64ff37) Delete clusterRoleBinding and serviceAccount.
 * [7bb99ae7](https://github.com/argoproj/argo-workflows/commit/7bb99ae713da51c9b9818027066f7ddd8efb92bb) Rename references from v1 to v1alpha1 in YAML
 * [32343913](https://github.com/argoproj/argo-workflows/commit/3234391356ae0eaf88d348b564828c2df754a49e) Implement step artifacts tab (#534)
 * [b2a58dad](https://github.com/argoproj/argo-workflows/commit/b2a58dad98942ad06b0431968be00ebe588818ff) Workflow list (#533)
 * [5dd1754b](https://github.com/argoproj/argo-workflows/commit/5dd1754b4a41c7951829dbbd8e70a244cf627331) Guard controller from informer sending non workflow/pod objects (#505)
 * [59e31c60](https://github.com/argoproj/argo-workflows/commit/59e31c60f8675c2c678c50e9694ee993691b6e6a) Enable resync period in workflow/pod informers (resolves #532)
 * [d5b06dcd](https://github.com/argoproj/argo-workflows/commit/d5b06dcd4e52270a24f4f3b19497b9a9afaed4e9) Significantly increase efficiency of workflow control loop (resolves #505)
 * [4b2098ee](https://github.com/argoproj/argo-workflows/commit/4b2098ee271301eca52403e769f82f6d717400af) finished walkthrough sections
 * [eb7292b0](https://github.com/argoproj/argo-workflows/commit/eb7292b02414ef6faca4f424f6b04ea444abb0e0) walkthrough
 * [82b1c7d9](https://github.com/argoproj/argo-workflows/commit/82b1c7d97536baac7514d7cfe72d1be9309bef43) Add -o wide option to `argo get` to display artifacts and durations (resolves #526)
 * [3427955d](https://github.com/argoproj/argo-workflows/commit/3427955d35bf6babc0bfee958a2eb417553ed203) Use PATCH api from k8s go SDK for annotating/labeling pods
 * [4842bbbc](https://github.com/argoproj/argo-workflows/commit/4842bbbc7e40340de12c788cc770eaa811431818) Add support for nodeSelector at both the workflow and step level (resolves #458)
 * [424fba5d](https://github.com/argoproj/argo-workflows/commit/424fba5d4c26c448c8c8131b89113c4c5fbae08d) Rename apiVersion of workflows from v1 to v1alpha1 (resolves #517)
 * [5286728a](https://github.com/argoproj/argo-workflows/commit/5286728a98236c5a8883850389d286d67549966e) Propogate executor errors back to controller. Add error column in `argo get` (#522)
 * [32b5e99b](https://github.com/argoproj/argo-workflows/commit/32b5e99bb194e27a8a35d1d7e1378dd749cc546f) Simplify executor commands to just 'init' and 'wait'. Improve volumes examples
 * [e2bfbc12](https://github.com/argoproj/argo-workflows/commit/e2bfbc127d03f5ef20763fe8a917c82e3f06638d) Update controller config automatically on configmap updates resolves #461
 * [c09b13f2](https://github.com/argoproj/argo-workflows/commit/c09b13f21eaec4bb78c040134a728d8e021b4d1e) Workflow validation detects when arguments were not supplied (#515)
 * [705193d0](https://github.com/argoproj/argo-workflows/commit/705193d053cb8c0c799a0f636fc899e8b7f55bcc) Proper message for non-zero exits from main container. Indicate an Error phase/message when failing to load/save artifacts
 * [e69b7510](https://github.com/argoproj/argo-workflows/commit/e69b7510196daba3a87dca0c8a9677abd8d74675) Update page title and favicon (#519)
 * [4330232f](https://github.com/argoproj/argo-workflows/commit/4330232f51d404a7546cf24b4b0eb608bf3113f5) Render workflow steps on workflow list page (#518)
 * [87c447ea](https://github.com/argoproj/argo-workflows/commit/87c447eaf2ca2230e9b24d6af38f3a0fd3c520c3) Implement kube api proxy. Add workflow node logs tab (#511)
 * [0ab26883](https://github.com/argoproj/argo-workflows/commit/0ab268837cff2a1fd464673a45c3736178917be5) Rework/rename Makefile targets. Bake in image namespace/tag set during build, as part of argo install
 * [3f13f5ca](https://github.com/argoproj/argo-workflows/commit/3f13f5cabe9dc54c7fbaddf7b0cfbcf91c3f26a7) Support for overriding/supplying entrypoint and parameters via argo CLI. Update examples
 * [6f9f2adc](https://github.com/argoproj/argo-workflows/commit/6f9f2adcd017954a72b2b867e6bc2bcba18972af) Support ListOptions in the WorkflowClient. Add flag to delete completed workflows
 * [30d7fba1](https://github.com/argoproj/argo-workflows/commit/30d7fba1205e7f0b4318d6b03064ee647d16ce59) Check Kubernetes version.
 * [a3909273](https://github.com/argoproj/argo-workflows/commit/a3909273c435b23de865089b82b712e4d670a4ff) Give proper error for unamed steps
 * [eed54f57](https://github.com/argoproj/argo-workflows/commit/eed54f5732a61922f6daff9e35073b33c1dc068e) Harden the IsURL check
 * [bfa62afd](https://github.com/argoproj/argo-workflows/commit/bfa62afd857704c53aef32f5ade7df86cf2c0769) Add phase,completed fields to workflow labels. Add startedAt,finishedAt,phase,message to workflow.status
 * [9347619c](https://github.com/argoproj/argo-workflows/commit/9347619c7c125950a9f17acfbd92a1286bca1a57) Create serviceAccount & roleBinding if necessary.
 * [205e5cbc](https://github.com/argoproj/argo-workflows/commit/205e5cbce20a6e5e73c977f1e775671a19bf4434) Introduce 'completed' pod label and label selector so controller can ignore completed pods
 * [199dbcbf](https://github.com/argoproj/argo-workflows/commit/199dbcbf1c3fa2fd452e5c36035d0f0ae8cdde42) 476 jobs list page (#501)
 * [05879294](https://github.com/argoproj/argo-workflows/commit/0587929453ac10d7318a91f2243aece08fe84129) Implement workflow tree tab draft (#494)
 * [a2f034a0](https://github.com/argoproj/argo-workflows/commit/a2f034a063b30b0bb5d9e0f670a8bb38560880b4) Proper error reporting. Add message, startedAt, finishedAt to NodeStatus. Rename status to phase
 * [645fedca](https://github.com/argoproj/argo-workflows/commit/645fedcaf532e052ef0bfc64cb56bfb3307479dd) Support loop step expansion from input parameters and previous step results
 * [75c1c482](https://github.com/argoproj/argo-workflows/commit/75c1c4822b4037176aa6d3702a5cf4eee590c7b7) Help page v2 (#492)
 * [a4af6702](https://github.com/argoproj/argo-workflows/commit/a4af6702d526e775c0aa31ee3612328e5d058c2b) Basic state of  navigation, top-bar, tooltip for UI v2 (#491)
 * [726e9fa0](https://github.com/argoproj/argo-workflows/commit/726e9fa0953fe91eb0401727743a04c8a02668ef) moved the service acct note
 * [3a4cd9c4](https://github.com/argoproj/argo-workflows/commit/3a4cd9c4ba46f586a3d26fbe017d4d3002e6b671) 477 job details page (#488)
 * [8ba7b55c](https://github.com/argoproj/argo-workflows/commit/8ba7b55cb59173ff7470be3451cd38333539b182) Edited the instructions
 * [1e9dbdba](https://github.com/argoproj/argo-workflows/commit/1e9dbdbabbe354f9798162854dd7d6ae4aa8539a) Added influxdb-ci example
 * [bd5c0baa](https://github.com/argoproj/argo-workflows/commit/bd5c0baad83328f13f25ba59e15a5f607d2fb9eb) Added comment for entrypoint field
 * [2fbecdf0](https://github.com/argoproj/argo-workflows/commit/2fbecdf0484a9e3c0d9242bdd7286f83b6e771eb) Argo V2 UI initial commit (#474)
 * [da4ef06e](https://github.com/argoproj/argo-workflows/commit/da4ef06e14c55a3ffc80bcdbd1b637a984f2f0f9) added artifact to ci example
 * [9ce20123](https://github.com/argoproj/argo-workflows/commit/9ce2012303aa30623336f0dde72ad9b80a5409e3) added artifacts
 * [caaa32a6](https://github.com/argoproj/argo-workflows/commit/caaa32a6b3c28c4f5a43514799b26528b55197ee) Minor edit
 * [ae72b583](https://github.com/argoproj/argo-workflows/commit/ae72b583852e43f616d4c021a4e5646235d4c0b4) added more argo/kubectl examples
 * [1db21612](https://github.com/argoproj/argo-workflows/commit/1db21612695a0a9170e265232acc19936b0d7294) merged
 * [8df393ed](https://github.com/argoproj/argo-workflows/commit/8df393ed78d1e4353ee30ba02cec0b12daea7eb0) added 2.0
 * [9e3a51b1](https://github.com/argoproj/argo-workflows/commit/9e3a51b14d78c3622543429a500a7d0367b10787) Update demo.md to have better instructions to restart controller after configuration changes
 * [ba9f9277](https://github.com/argoproj/argo-workflows/commit/ba9f9277a4a9a153a6f5b19862a73364f618e5cd) Add demo markdown file. Delete old demo.txt
 * [d8de40bb](https://github.com/argoproj/argo-workflows/commit/d8de40bb14167f30b17de81d6162d633a62e7a0d) added 2.0
 * [6c617599](https://github.com/argoproj/argo-workflows/commit/6c617599bf4c91ccd3355068967824c1e8d7c107) added 2.0
 * [32af692e](https://github.com/argoproj/argo-workflows/commit/32af692eeec765b13ee3d2b4ede9f5ff45527b4c) added 2.0
 * [802940be](https://github.com/argoproj/argo-workflows/commit/802940be0d4ffd5048dd5307b97af442d82e9a83) added 2.0
 * [1d443415](https://github.com/argoproj/argo-workflows/commit/1d44341553d95ac8192d4a80e178a9d72558829a) added new png

### Contributors

 * Alexander Matyushentsev
 * Ed Lee
 * Jesse Suen
 * Rafal
 * Sandeep Bhojwani
 * Shri Javadekar
 * Wojciech Kalemba
 * cyee88
 * mukulikak

## v2.0.0-alpha1 (2017-11-16)


### Contributors


## v2.0.0 (2018-02-06)

 * [0978b9c6](https://github.com/argoproj/argo-workflows/commit/0978b9c61cb7435d31ef8d252b80e03708a70adc) Support setting UI base Url  (#722)
 * [b75cd98f](https://github.com/argoproj/argo-workflows/commit/b75cd98f6c038481ec3d2253e6404952bcaf4bd5) updated argo-user slack link
 * [b3598d84](https://github.com/argoproj/argo-workflows/commit/b3598d845c4cdb9ac7c4ae5eff5024ecd3fc5fd6) Add examples as functional and expected failure e2e tests
 * [83966e60](https://github.com/argoproj/argo-workflows/commit/83966e6095e2468368b0929613e7371074ee972b) Fix regression where executor did not annotate errors correctly
 * [751fd270](https://github.com/argoproj/argo-workflows/commit/751fd27024d9f3bfc40051d2ca694b25a42307ea) Update UI references to v2.0.0. Update changelog
 * [8b7e2e24](https://github.com/argoproj/argo-workflows/commit/8b7e2e24e8cf7ae6b701f08b0702ac045e0336f8) Check-in the OpenAPI spec. Automate generation as part of `make update-codegen`
 * [563bda75](https://github.com/argoproj/argo-workflows/commit/563bda756732802caeaa516fd0c493c6e07f6cf9) Fix update-openapigen.sh script to presume bash. Tweak documentation
 * [5b9a602b](https://github.com/argoproj/argo-workflows/commit/5b9a602b4a763ac633f7ede86f13253451855462) Add documentation to types. Add program to generate OpenAPI spec
 * [d929e79f](https://github.com/argoproj/argo-workflows/commit/d929e79f623017a923d1c4e120c363e08fe7a64a) Generate OpenAPI models for the workflow spec (issue #707)
 * [1d5afee6](https://github.com/argoproj/argo-workflows/commit/1d5afee6ea48743bb854e69ffa333f361e52e289) Shortened url
 * [617d848d](https://github.com/argoproj/argo-workflows/commit/617d848da27d0035c20f21f3f6bddbe0e04550db) Added news to README
 * [ae36b22b](https://github.com/argoproj/argo-workflows/commit/ae36b22b6d0d0ce8c230aedcce0814489162ae5b) Fix typo s/Customer/Custom/ (#704)
 * [5a589fcd](https://github.com/argoproj/argo-workflows/commit/5a589fcd932116720411d53aeb6454e297456e06) Add ability to specify imagePullSecrets in the workflow.spec (resolves #699)
 * [2f77bc1e](https://github.com/argoproj/argo-workflows/commit/2f77bc1ed00042388d0492cfd480d7c22599112c) Add ability to specify affinity rules at both the workflow and template level (resolves #701)
 * [fdafbe27](https://github.com/argoproj/argo-workflows/commit/fdafbe27e5e2f4f2d58913328ae22db9a6c363b4) Sidecars unable to reference volume claim templates (resolves #697)
 * [0b0b52c3](https://github.com/argoproj/argo-workflows/commit/0b0b52c3b45cbe5ac62da7b26b30d19fc1f9eb3e) Referencing output artifacts from a container with retries was not functioning (resolves #698)
 * [bf2b376a](https://github.com/argoproj/argo-workflows/commit/bf2b376a142ed4fdf70ba4f3702533e7b75fc6b2) Update doc references to point to v2.0.0-beta1. Fix secrets example
 * [549870c1](https://github.com/argoproj/argo-workflows/commit/549870c1ee08138b20b8a4b0c026569cf1e6c19a) Fix argo-ui download links to point to v2.0.0-beta1
 * [a202049d](https://github.com/argoproj/argo-workflows/commit/a202049d327c64e282a37d7598bddc1faa1a3c1a) Update CHANGELOG for v2.0.0-beta1
 * [a3739035](https://github.com/argoproj/argo-workflows/commit/a3739035f8e1f517721489fc53b58a8e27a575e1) Remove dind requirement from argo-ci test steps
 * [1bdd0c03](https://github.com/argoproj/argo-workflows/commit/1bdd0c03dbb9d82ad841ca19be6e1ea93aeb82f7) Include completed pods when attempting to reconcile deleted pods Switch back to Patch (from Update) for persisting workflow changes
 * [a4a43892](https://github.com/argoproj/argo-workflows/commit/a4a4389219cbe84e3bc7b3731cdfccb9ee5f5730) Sleep 1s after persisting workflow to give informer cache a chance to sync (resolves #686)
 * [5bf49531](https://github.com/argoproj/argo-workflows/commit/5bf49531f99ef9d8b8aefeac26a4a3fa0177e70d) Updated demo.md with link to ARTIFACT_REPO.md
 * [863d547a](https://github.com/argoproj/argo-workflows/commit/863d547a1a2a146a898c06c835187e0595af5689) Rely on controller generated timestamps for node.StartedAt instad of pod.CreationTimestamp
 * [672542d1](https://github.com/argoproj/argo-workflows/commit/672542d1f08c206f89f8747e9b14b675cdd77446) Re-apply workflow changes and reattempt update on resource conflicts. Make completed pod labeling asynchronous
 * [81bd6d3d](https://github.com/argoproj/argo-workflows/commit/81bd6d3d46d2fd7ea57aa095ae134116cfca90f2) Resource state retry (#690)
 * [44dba889](https://github.com/argoproj/argo-workflows/commit/44dba889cb743552557fcd7453ee81a89875142d) Tune controller to 20 QPS, 30 Burst, 8 wf workers, 8 pod workers
 * [178b9d37](https://github.com/argoproj/argo-workflows/commit/178b9d37cc452af214df7c9c41522124c117e7a3) Show running/completed pod counts in `argo list -o wide`
 * [0c565f5f](https://github.com/argoproj/argo-workflows/commit/0c565f5f5e9f69244e9828ced7c3916ac605f460) Switch to Updating workflow resources instead of Patching (resolves #686)
 * [a571f592](https://github.com/argoproj/argo-workflows/commit/a571f592fa131771b8d71126fc27809e24462cfe) Ensure sidecars get killed unequivocally. Final argoexec stats were not getting printed
 * [a0b2d78c](https://github.com/argoproj/argo-workflows/commit/a0b2d78c869f277c20c4cd3ba18b8d2688674e54) Show duration by default in `argo get`. --since flag should always include Running
 * [10110313](https://github.com/argoproj/argo-workflows/commit/101103136287b8ee16a7afda94cc6ff59be07ef6) Executor hardening: add retries and memoization for executor k8s API calls Recover from unexpected panics and annotate the error.
 * [f2b8f248](https://github.com/argoproj/argo-workflows/commit/f2b8f248ab8d483e0ba41a287611393500c7b507) Regenerate deepcopy code after type changes for raw input artifacts
 * [322e0e3a](https://github.com/argoproj/argo-workflows/commit/322e0e3aa3cb2e650f3ad4b7ff9157f71a92e8b4) renamed file as per review comment
 * [0a386cca](https://github.com/argoproj/argo-workflows/commit/0a386ccaf705a1abe1f9239adc966fceb7a808ae) changes from the review - renamed "contents" to "data" - lint issue
 * [d9ebbdc1](https://github.com/argoproj/argo-workflows/commit/d9ebbdc1b31721c8095d3c5426c1c811054a94a7) support for raw input as artifact
 * [a1f821d5](https://github.com/argoproj/argo-workflows/commit/a1f821d589d47ca5b12b94ad09306a706a43d150) Introduce communication channel from workflow-controller to executor through pod annotations
 * [b324f9f5](https://github.com/argoproj/argo-workflows/commit/b324f9f52109b9aa29bc89d63810be6e421eb54f) Artifactory repository was not using correct casing for repoURL field
 * [3d45d25a](https://github.com/argoproj/argo-workflows/commit/3d45d25ac497a09fa291d20f867a75f59b6abf92) Add `argo list --since` to filter workflows newer than a relative duration
 * [cc2efdec](https://github.com/argoproj/argo-workflows/commit/cc2efdec368c2f133c076a9eda9065f64762a9fa) Add ability to set loglevel of controller via CLI flag
 * [60c124e5](https://github.com/argoproj/argo-workflows/commit/60c124e5dddb6ebfee6300d36f6a3877838ec17c) Remove hack.go and use dep to install code-generators
 * [d14755a7](https://github.com/argoproj/argo-workflows/commit/d14755a7c5f583c1f3c8c762ae8628e780f566cf) `argo list` was not handling the default case correctly
 * [472f5604](https://github.com/argoproj/argo-workflows/commit/472f5604e27ca6310e016f846c97fda5d7bca9dd) Improvements to `argo list` * sort workflows by running vs. completed, then by finished time * add --running, --completed, --status XXX filters * add -o wide option to show parameters and -o name to show only the names
 * [b063f938](https://github.com/argoproj/argo-workflows/commit/b063f938f34f650333df6ec5a2e6a325a5b45299) Use minimal ClusterRoles for workflow-controller and argo-ui deployments
 * [21bc2bd0](https://github.com/argoproj/argo-workflows/commit/21bc2bd07ebbfb478c87032e2ece9939ea436030) Added link to configuring artifact repo from main README
 * [b54bc067](https://github.com/argoproj/argo-workflows/commit/b54bc067bda02f95937774fb3345dc2010d3efc6) Added link to configuring artifact repo from main README
 * [58ec5169](https://github.com/argoproj/argo-workflows/commit/58ec51699534e73d82c3f44027326b438cf5c063) Updated ARTIFACT_REPO.md
 * [1057d087](https://github.com/argoproj/argo-workflows/commit/1057d087838bcbdbffc70367e0fc02778907c9af) Added detailed instructions on configuring AWS and GCP artifact rpos
 * [b0a7f0da](https://github.com/argoproj/argo-workflows/commit/b0a7f0da85fabad34814ab129eaba43862a1d2dd) Issue 680 - Argo UI is failing to render workflow which has not been picked up by workflow controller (#681)
 * [e91c227a](https://github.com/argoproj/argo-workflows/commit/e91c227acc1f86b7e341aaac534930f9b529cd89) Document and clarify artifact passing (#676)
 * [290f6799](https://github.com/argoproj/argo-workflows/commit/290f6799752ef602b27c193212495e27f40dd687) Allow containers to be retried. (#661)
 * [80f9b1b6](https://github.com/argoproj/argo-workflows/commit/80f9b1b636704ebad6ebb8df97c5e81dc4f815f9) Improve the error message when insufficent RBAC privileges is detected (resolves #659)
 * [3cf67df4](https://github.com/argoproj/argo-workflows/commit/3cf67df422f34257296d2de09d2ca3c8c87abf84) Regenerate autogenerated code after changes to types
 * [baf37052](https://github.com/argoproj/argo-workflows/commit/baf37052976458401a6c0e44d06f30dc8d819680) Add support for resource template outputs. Remove output.parameters.path in favor of valueFrom
 * [dc1256c2](https://github.com/argoproj/argo-workflows/commit/dc1256c2034f0add4bef3f82ce1a71b454d4eef5) Fix expected file name for issue template
 * [a492ad14](https://github.com/argoproj/argo-workflows/commit/a492ad14177eb43cdd6c2a017c9aec87183682ed) Add a GitHub issues template
 * [55be93a6](https://github.com/argoproj/argo-workflows/commit/55be93a68d8991f76a31adaf49f711436a35a9d0) Add a --dry-run option to `argo install`. Remove CRD creation from controller startup
 * [fddc052d](https://github.com/argoproj/argo-workflows/commit/fddc052df8a3478aede67057f2b06938c2a6a7a4) Fix README.md to contain influxdb-client in the example (#669)
 * [67236a59](https://github.com/argoproj/argo-workflows/commit/67236a5940231f7b9dc2ca2f4cb4cb70b7c18d45) Update getting started doc to use `brew install` and better instructions for RBAC clusters (resolves #654, #530)
 * [5ac19753](https://github.com/argoproj/argo-workflows/commit/5ac19753846566d0069b76e3e6c6dd03f0e6950c) Support rendering retry steps (#670)
 * [3cca0984](https://github.com/argoproj/argo-workflows/commit/3cca0984c169ea59e8e2758a04550320b1981875) OpenID Connect auth support (#663)
 * [c222cb53](https://github.com/argoproj/argo-workflows/commit/c222cb53a168f9bd40b7731d0b2f70db977990c2) Clarify where the Minio secret comes from.
 * [a78e2e8d](https://github.com/argoproj/argo-workflows/commit/a78e2e8d551d6afad2e0fbce7a9f0a1bd023c11b) Remove parallel steps that use volumes.
 * [35517385](https://github.com/argoproj/argo-workflows/commit/355173857f98a9a9704ab23235b3186bde8092b9) Prevent a potential k8s scheduler panic from incomplete setting of pod ownership reference (resolves #656)
 * [1a8bc26d](https://github.com/argoproj/argo-workflows/commit/1a8bc26d40597f2f0475aa9197a6b3912c5bbb56) Updated README
 * [9721fca0](https://github.com/argoproj/argo-workflows/commit/9721fca0e1ae9d1d57aa8d1872450ce8ee7487e2) Updated README
 * [e3177606](https://github.com/argoproj/argo-workflows/commit/e3177606105a936da7eba29924fa49ad497703c9) Fix typos in READMEs
 * [555d50b0](https://github.com/argoproj/argo-workflows/commit/555d50b0ebeef1c753394de974dad2e0d4a5b787) Simplify some getting started instructions. Correct some usages of container resources field
 * [4abc9c40](https://github.com/argoproj/argo-workflows/commit/4abc9c40e7656a5783620e41b33e4ed3bb7249e2) Updated READMEs
 * [a0add24f](https://github.com/argoproj/argo-workflows/commit/a0add24f9778789473b2b097fb31a56ae11bfce9) Switch to k8s-codegen generated workflow client and informer
 * [9b08b6e9](https://github.com/argoproj/argo-workflows/commit/9b08b6e997633d5f2e94392f000079cbe93ee023) Added link for argoproj slack channel
 * [682bbdc0](https://github.com/argoproj/argo-workflows/commit/682bbdc09b66698090d309e91b5caf4483931e34) Update references to point to latest argo release
 * [940dd56d](https://github.com/argoproj/argo-workflows/commit/940dd56d98c75eb93da3b5de598882754cb74fc7) Fix artifactory unit test and linting issues
 * [e7ba2b44](https://github.com/argoproj/argo-workflows/commit/e7ba2b44114fca8a3cb2b8635dc2fdfeaa440d9e) Update help page links (#651)
 * [53dac4c7](https://github.com/argoproj/argo-workflows/commit/53dac4c74933c333124a0cb1d8cf6c9255f9199d) Add artifactory and UI fixes to 2.0.0-alpha3 CHANGELOG
 * [4b4eff43](https://github.com/argoproj/argo-workflows/commit/4b4eff43f20ed678d34efe567a4d61d1364d7124) Allow disabling web console feature (#649)
 * [90b7f2e6](https://github.com/argoproj/argo-workflows/commit/90b7f2e67dddebba1678e215bde75d68867b4469) Added support for artifactory
 * [849e916e](https://github.com/argoproj/argo-workflows/commit/849e916e5bf98f320f1a65b12ffe246d9ebbb6f6) Adjusted styles for logs stream (#614)
 * [a8a96030](https://github.com/argoproj/argo-workflows/commit/a8a960303423cde2e511d4af9c2c8ae834076b21) Update CHANGELOG for 2.0.0-alpha3
 * [e7c7678c](https://github.com/argoproj/argo-workflows/commit/e7c7678cc605285e5b3224c757e5e4be57ab4d5c) Fix issue preventing ability to pass JSON as a command line param (resolves #646)
 * [7f5e2b96](https://github.com/argoproj/argo-workflows/commit/7f5e2b96bd96e0bccf4778383aa9b94a1768e9c0) Add validation checks for volumeMount/artifact path collision and activeDeadlineSeconds (#620)
 * [dc4a9463](https://github.com/argoproj/argo-workflows/commit/dc4a94633c4d00d78a7ea53272e425962de405ba) Add the ability to specify the service account used by pods in the workflow (resolves #634) Also add argo CLI support for supplying/overriding spec.serviceAccountName from command line.
 * [16f7000a](https://github.com/argoproj/argo-workflows/commit/16f7000aa77b2759fa0a65d6e42456bcb660f824) Workflow operator will recover from unexpected panics and mark the workflow with error (resolves #633)
 * [18dca7fe](https://github.com/argoproj/argo-workflows/commit/18dca7fe21d57e6a5415c53bfdb87a889ac32456) Issue #629 - Add namespace to workflow list and workflow details page (#639)
 * [e656bace](https://github.com/argoproj/argo-workflows/commit/e656bace75aaa859f04121f2c1d95631b462fe62) Issue #637 -  Implement Workflow list and workflow details page live update (#638)
 * [1503ce3a](https://github.com/argoproj/argo-workflows/commit/1503ce3aee40eba741819a1403847df4bbcb7b23) Issue #636 - Upgrade to ui-lib 2.0.3 to fix xterm incompatibility (#642)
 * [f9170e8a](https://github.com/argoproj/argo-workflows/commit/f9170e8abb7121b0d0cbc3e4c07b9bdc2224fb76) Remove manifest-passing.yaml example now that we have resource templates
 * [25be5fd6](https://github.com/argoproj/argo-workflows/commit/25be5fd6368bac3fde8e4392b3cb9d4159983a1a) Implementation for resource templates and resource success/failure conditions
 * [402ad565](https://github.com/argoproj/argo-workflows/commit/402ad565f4a3b95c449ddd4c6dc468947aeb7192) Updated examples/README
 * [8536c7fc](https://github.com/argoproj/argo-workflows/commit/8536c7fc89a0ceb39208efe2076919d0390e3d2e) added secret example to examples/README
 * [e5002b82](https://github.com/argoproj/argo-workflows/commit/e5002b8286af2c1f7ec64953114e1d97c889ca37) Add '--wait' to argo submit.
 * [9646e55f](https://github.com/argoproj/argo-workflows/commit/9646e55f8bb8fbac80d456853aa891c2ae069adb) Installer was not update configmap correctly with new executor image during upgrade
 * [69d72913](https://github.com/argoproj/argo-workflows/commit/69d72913a3a72bbf7b075be847303305b4bef1a5) Support private git repos using secret selector fields in the git artifact (resolves #626)
 * [64e17244](https://github.com/argoproj/argo-workflows/commit/64e17244ef04b9d2aa6abf6f18d4e7ef2d20ff37) Add argo ci workflow (#619)
 * [e8998435](https://github.com/argoproj/argo-workflows/commit/e8998435598e8239d7b77a60cfda43e8f2869b4d) Resolve controller panic when a script template with an input artifact was submitted (resolves #617). Utilize the kubernetes.Interface and fake.Clientset to support unit test mocking. Added a unit test to reproduce the panic. Add an e2e test to verify functionality works.
 * [52075b45](https://github.com/argoproj/argo-workflows/commit/52075b45611783d909609433bb44702888b5db37) Introduce controller instance IDs to support multiple workflow controllers in a cluster (resolves #508)
 * [133a23ce](https://github.com/argoproj/argo-workflows/commit/133a23ce20b4570ded81fac76a430f0399c1eea1) Add ability to timeout a container/script using activeDeadlineSeconds
 * [b5b16e55](https://github.com/argoproj/argo-workflows/commit/b5b16e55260df018cc4de14bf298ce59714b4396) Support for workflow exit handlers
 * [906b3e7c](https://github.com/argoproj/argo-workflows/commit/906b3e7c7cac191f920016362b076a28f18d97c1) Update ROADMAP.md
 * [5047422a](https://github.com/argoproj/argo-workflows/commit/5047422ae71869672c84364d099e1488b29fbbe8) Update CHANGELOG.md
 * [2b6583df](https://github.com/argoproj/argo-workflows/commit/2b6583dfb02911965183ef4b25ed68c867448e10) Add `argo wait` for waiting on workflows to complete. (#618)
 * [cfc9801c](https://github.com/argoproj/argo-workflows/commit/cfc9801c40528b6605823e1f4b4359600b6887df) Add option to print output of submit in json.
 * [c20c0f99](https://github.com/argoproj/argo-workflows/commit/c20c0f9958ceeefd3597120fcb4013d857276076) Comply with semantic versioning. Include build metadata in `argo version` (resolves #594)
 * [bb5ac7db](https://github.com/argoproj/argo-workflows/commit/bb5ac7db52bff613c32b153b82953ec9c73c3b8a) minor change
 * [91845d49](https://github.com/argoproj/argo-workflows/commit/91845d4990ff8fd97bd9404e4b37024be1ee0ba6) Added more documentation
 * [4e8d69f6](https://github.com/argoproj/argo-workflows/commit/4e8d69f630bc0fd107b360ee9ad953ccb0b78f11) fixed install instructions
 * [0557147d](https://github.com/argoproj/argo-workflows/commit/0557147dd4bfeb2688b969293ae858a8391d78ad) Removed empty toolbar (#600)
 * [bb2b29ff](https://github.com/argoproj/argo-workflows/commit/bb2b29ff5e4178e2c8a9dfe666b699d75aa9ab3b) Added limit for number of steps in workflows list (#602)
 * [3f57cc1d](https://github.com/argoproj/argo-workflows/commit/3f57cc1d2ff9c0e7ec40da325c3478a8037a6ac0) fixed typo in examples/README
 * [ebba6031](https://github.com/argoproj/argo-workflows/commit/ebba6031192b0a763bd94b1625a2ff6e242f112e) Updated examples/README.md with how to override entrypoint and parameters
 * [81834db3](https://github.com/argoproj/argo-workflows/commit/81834db3c0bd12758a95e8a5862d6dda6d0dceeb) Example with using an emptyDir volume.
 * [4cd949d3](https://github.com/argoproj/argo-workflows/commit/4cd949d327ddb9d4f4592811c51e07bb53b30ef9) Remove apiserver
 * [6a916ca4](https://github.com/argoproj/argo-workflows/commit/6a916ca447147e4aff364ce032c9db4530d49d11) `argo lint` did not split yaml files. `argo submit` was not ignoring non-workflow manifests
 * [bf7d9979](https://github.com/argoproj/argo-workflows/commit/bf7d997970e967b2b238ce209ce823ea47de01d2) Include `make lint` and `make test` as part of CI
 * [d1639ecf](https://github.com/argoproj/argo-workflows/commit/d1639ecfabf73f73ebe040b832668bd6a7b60d20) Create example workflow using kubernetes secrets (resolves #592)
 * [31c54af4](https://github.com/argoproj/argo-workflows/commit/31c54af4ba4cb2a0db918fadf62cb0b854592ba5) Toolbar and filters on workflows list (#565)
 * [bb4520a6](https://github.com/argoproj/argo-workflows/commit/bb4520a6f65d4e8e765ce4d426befa583721c194) Add and improve the inlined comments in example YAMLs
 * [a0470728](https://github.com/argoproj/argo-workflows/commit/a04707282cdeadf463b22b633fc00dba432f60bf) Fixed typo.
 * [13366e32](https://github.com/argoproj/argo-workflows/commit/13366e32467a34a061435091589c90d04a84facb) Fix some wrong GOPATH assumptions in Makefile. Add `make test` target. Fix unit tests
 * [9f4f1ee7](https://github.com/argoproj/argo-workflows/commit/9f4f1ee75705150a22dc68a3dd16fa90069219ed) Add 'misspell' to linters. Fix misspellings caught by linter
 * [1b918aff](https://github.com/argoproj/argo-workflows/commit/1b918aff29ff8e592247d14c52be06a0537f0734) Address all issues in code caught by golang linting tools (resolves #584)
 * [903326d9](https://github.com/argoproj/argo-workflows/commit/903326d9103fa7dcab37835a9478f58aff51a5d1) Add manifest passing to do kubectl create with dynamic manifests (#588)
 * [b1ec3a3f](https://github.com/argoproj/argo-workflows/commit/b1ec3a3fc90a211f9afdb9090d4396c98ab3f71f) Create the argo-ui service with type ClusterIP as part of installation (resolves #582)
 * [5b6271bc](https://github.com/argoproj/argo-workflows/commit/5b6271bc56b46a82b0ee2bc0784315ffcddeb27f) Add validate names for various workflow specific fields and tests for them (#586)
 * [b6e67131](https://github.com/argoproj/argo-workflows/commit/b6e671318a446f129740ce790f53425d65e436f3) Implementation for allowing access to global parameters in workflow (#571)
 * [c5ac5bfb](https://github.com/argoproj/argo-workflows/commit/c5ac5bfb89274fb5ee85f9cef346b7059b5d7641) Fix error message when key does not exist in secret (resolves #574). Improve s3 example and documentation.
 * [4825c43b](https://github.com/argoproj/argo-workflows/commit/4825c43b3e0c3c54b2313aa54e69520ed1b8a38d) Increate UI build memory limit (#580)
 * [87a20c6b](https://github.com/argoproj/argo-workflows/commit/87a20c6bce9a6bfe2a88edc581746ff5f7f006fc) Update input-artifacts-s3.yaml example to explain concepts and usage better
 * [c16a9c87](https://github.com/argoproj/argo-workflows/commit/c16a9c87102fd5b66406737720204e5f17af0fd1) Rahuldhide patch 2 (#579)
 * [f5d0e340](https://github.com/argoproj/argo-workflows/commit/f5d0e340b3626658b435dd2ddd937e97af7676b2) Issue #549 - Prepare argo v1 build config (#575)
 * [3b3a4c87](https://github.com/argoproj/argo-workflows/commit/3b3a4c87bd3138961c948f869e2c5b7c932c8847) Argo logo
 * [d1967443](https://github.com/argoproj/argo-workflows/commit/d1967443a4943f685f6cb1649480765050bdcdaa) Skip e2e tests if Kubeconfig is not provided.
 * [1ec231b6](https://github.com/argoproj/argo-workflows/commit/1ec231b69a1a7d985d1d587980c34588019b04aa) Create separate namespaces for tests.
 * [5ea20d7e](https://github.com/argoproj/argo-workflows/commit/5ea20d7eb5b9193c19f7c875c8fb2f4af8f68ef3) Add a deadline for workflow operation to prevent workqueue starvation and to enable state resync (#531) Tested with 6 x 1000 pod workflows.
 * [346bafe6](https://github.com/argoproj/argo-workflows/commit/346bafe636281bca94695b285767f41ae71e6a69) Multiple scalability improvements to controller (resolves #531)
 * [bbc56b59](https://github.com/argoproj/argo-workflows/commit/bbc56b59e2ff9635244bcb091e92e257a508d147) Improve argo ui build performance and reduce image size (#572)
 * [cdb1ce82](https://github.com/argoproj/argo-workflows/commit/cdb1ce82bce9b103e433981d94bd911b0769350d) Upgrade ui-lib (#556)
 * [0605ad7b](https://github.com/argoproj/argo-workflows/commit/0605ad7b33fc4f9c0bbff79adf1d509d3b072703) Adjusted tabs content size to see horizontal and vertical scrolls. (#569)
 * [a3316236](https://github.com/argoproj/argo-workflows/commit/a331623697e76a5e3497257e28fabe1995852339) Fix rendering 'Error' node status (#564)
 * [8c3a7a93](https://github.com/argoproj/argo-workflows/commit/8c3a7a9393d619951a676324810d482d28dfe015) Issue #548  - UI terminal window  (#563)
 * [5ec6cc85](https://github.com/argoproj/argo-workflows/commit/5ec6cc85aab63ea2277ce621d5de5b59a510d462) Implement API to ssh into pod (#561)
 * [beeb65dd](https://github.com/argoproj/argo-workflows/commit/beeb65ddcb7d2b5f8286f7881af1f5c00535161e) Don't mess the controller's arguments.
 * [01f5db5a](https://github.com/argoproj/argo-workflows/commit/01f5db5a0c3dc48541577b9d8b1d815399728070) Parameterize Install() and related methods.
 * [85a2e271](https://github.com/argoproj/argo-workflows/commit/85a2e2711beba8f2c891af396a3cc886c7b37542) Fix tests.
 * [56f666e1](https://github.com/argoproj/argo-workflows/commit/56f666e1bf69a7f5d8191637e8c7f384b91d98d0) Basic E2e tests.
 * [9eafb9dd](https://github.com/argoproj/argo-workflows/commit/9eafb9dd59166e76804b71c8df19fdca453cdd28) Issue #547 - Support filtering by status in API GET /workflows (#550)
 * [37f41eb7](https://github.com/argoproj/argo-workflows/commit/37f41eb7bf366cfe007d3ecce7b21f003d381e34) Update demo.md
 * [ea8d5c11](https://github.com/argoproj/argo-workflows/commit/ea8d5c113d9245f47fe7b3d3f45e7891aa5f50e8) Update README.md
 * [373f0710](https://github.com/argoproj/argo-workflows/commit/373f07106ab14e3772c94af5cc11f7f1c7099204) Add support for making a no_ui build. Base all build on no_ui build (#553)
 * [ae65c57e](https://github.com/argoproj/argo-workflows/commit/ae65c57e55f92fd8ff1edd099f659e9e97ce59f1) Update demo.md
 * [f6f8334b](https://github.com/argoproj/argo-workflows/commit/f6f8334b2b3ed1f498c19e4de25421f41807f893) V2 style adjustments and small fixes (#544)
 * [12d5b7ca](https://github.com/argoproj/argo-workflows/commit/12d5b7ca48c913e53b74708a35727d523dfa5355) Document argo ui service creation (#545)
 * [3202d4fa](https://github.com/argoproj/argo-workflows/commit/3202d4fac2d5d2d2a3ad1d679c1b753b04aca796) Support all namespaces (#543)
 * [b553c1bd](https://github.com/argoproj/argo-workflows/commit/b553c1bd9a00499915dbe5926194d67c7392b944) Update demo.md to qualify the minio endpoint with the default namespace
 * [4df7617c](https://github.com/argoproj/argo-workflows/commit/4df7617c2e97f2336195d6764259537be648b89b) Fix artifacts downloading (#541)
 * [12732200](https://github.com/argoproj/argo-workflows/commit/12732200fb1ed95608cdc0b14bd0802c524c7fa2) Update demo.md with references to latest release
 * [0e67b861](https://github.com/argoproj/argo-workflows/commit/0e67b8616444cf637d5b68e58eb6e068b721d34c) Add 'release' make target. Improve CLI help and set version from git tag. Uninstaller for UI
 * [8ab1d2e9](https://github.com/argoproj/argo-workflows/commit/8ab1d2e93ff969a1a01a06dcc3ac4aa04d3514aa) Install argo ui along with argo workflow controller (#540)
 * [f4af881e](https://github.com/argoproj/argo-workflows/commit/f4af881e55cff12888867bca9dff940c1bb16c26) Add make command to build argo ui (#539)
 * [5bb85814](https://github.com/argoproj/argo-workflows/commit/5bb858145e1c603494d8202927197d38b121311a) Add example description in YAML.
 * [fc23fcda](https://github.com/argoproj/argo-workflows/commit/fc23fcdaebc9049748d57ab178517d18eed4af7d) edit example README
 * [8dd294aa](https://github.com/argoproj/argo-workflows/commit/8dd294aa003ee1ffaa70cd7735b7d62c069eeb0f) Add example of GIF processing using ImageMagick
 * [ef8e9d5c](https://github.com/argoproj/argo-workflows/commit/ef8e9d5c234b1f889c4a2accbc9f24d58ce553b9) Implement loader (#537)
 * [2ac37361](https://github.com/argoproj/argo-workflows/commit/2ac37361e6620b37af09cd3e50ecc0fb3fb62a12) Allow specifying CRD version (#536)
 * [15b5542d](https://github.com/argoproj/argo-workflows/commit/15b5542d7cff2b0812830b16bcc5ae490ecc7302) Installer was not using the argo serviceaccount with the workflow-controller deployment. Make progress messages consistent
 * [f1471347](https://github.com/argoproj/argo-workflows/commit/f1471347d96838e0e13e47d0bc7fc04b3018d6f7) Add Yaml viewer (#535)
 * [685a576b](https://github.com/argoproj/argo-workflows/commit/685a576bd28bb269d727a10bf617bd1b08ea4ff0) Fix Gopkg.lock file following rewrite of git history at github.com/minio/go-homedir
 * [01ab3076](https://github.com/argoproj/argo-workflows/commit/01ab3076fe68ef62a9e3cc89b0e367cbdb64ff37) Delete clusterRoleBinding and serviceAccount.
 * [7bb99ae7](https://github.com/argoproj/argo-workflows/commit/7bb99ae713da51c9b9818027066f7ddd8efb92bb) Rename references from v1 to v1alpha1 in YAML
 * [32343913](https://github.com/argoproj/argo-workflows/commit/3234391356ae0eaf88d348b564828c2df754a49e) Implement step artifacts tab (#534)
 * [b2a58dad](https://github.com/argoproj/argo-workflows/commit/b2a58dad98942ad06b0431968be00ebe588818ff) Workflow list (#533)
 * [5dd1754b](https://github.com/argoproj/argo-workflows/commit/5dd1754b4a41c7951829dbbd8e70a244cf627331) Guard controller from informer sending non workflow/pod objects (#505)
 * [59e31c60](https://github.com/argoproj/argo-workflows/commit/59e31c60f8675c2c678c50e9694ee993691b6e6a) Enable resync period in workflow/pod informers (resolves #532)
 * [d5b06dcd](https://github.com/argoproj/argo-workflows/commit/d5b06dcd4e52270a24f4f3b19497b9a9afaed4e9) Significantly increase efficiency of workflow control loop (resolves #505)
 * [4b2098ee](https://github.com/argoproj/argo-workflows/commit/4b2098ee271301eca52403e769f82f6d717400af) finished walkthrough sections
 * [eb7292b0](https://github.com/argoproj/argo-workflows/commit/eb7292b02414ef6faca4f424f6b04ea444abb0e0) walkthrough
 * [82b1c7d9](https://github.com/argoproj/argo-workflows/commit/82b1c7d97536baac7514d7cfe72d1be9309bef43) Add -o wide option to `argo get` to display artifacts and durations (resolves #526)
 * [3427955d](https://github.com/argoproj/argo-workflows/commit/3427955d35bf6babc0bfee958a2eb417553ed203) Use PATCH api from k8s go SDK for annotating/labeling pods
 * [4842bbbc](https://github.com/argoproj/argo-workflows/commit/4842bbbc7e40340de12c788cc770eaa811431818) Add support for nodeSelector at both the workflow and step level (resolves #458)
 * [424fba5d](https://github.com/argoproj/argo-workflows/commit/424fba5d4c26c448c8c8131b89113c4c5fbae08d) Rename apiVersion of workflows from v1 to v1alpha1 (resolves #517)
 * [5286728a](https://github.com/argoproj/argo-workflows/commit/5286728a98236c5a8883850389d286d67549966e) Propogate executor errors back to controller. Add error column in `argo get` (#522)
 * [32b5e99b](https://github.com/argoproj/argo-workflows/commit/32b5e99bb194e27a8a35d1d7e1378dd749cc546f) Simplify executor commands to just 'init' and 'wait'. Improve volumes examples
 * [e2bfbc12](https://github.com/argoproj/argo-workflows/commit/e2bfbc127d03f5ef20763fe8a917c82e3f06638d) Update controller config automatically on configmap updates resolves #461
 * [c09b13f2](https://github.com/argoproj/argo-workflows/commit/c09b13f21eaec4bb78c040134a728d8e021b4d1e) Workflow validation detects when arguments were not supplied (#515)
 * [705193d0](https://github.com/argoproj/argo-workflows/commit/705193d053cb8c0c799a0f636fc899e8b7f55bcc) Proper message for non-zero exits from main container. Indicate an Error phase/message when failing to load/save artifacts
 * [e69b7510](https://github.com/argoproj/argo-workflows/commit/e69b7510196daba3a87dca0c8a9677abd8d74675) Update page title and favicon (#519)
 * [4330232f](https://github.com/argoproj/argo-workflows/commit/4330232f51d404a7546cf24b4b0eb608bf3113f5) Render workflow steps on workflow list page (#518)
 * [87c447ea](https://github.com/argoproj/argo-workflows/commit/87c447eaf2ca2230e9b24d6af38f3a0fd3c520c3) Implement kube api proxy. Add workflow node logs tab (#511)
 * [0ab26883](https://github.com/argoproj/argo-workflows/commit/0ab268837cff2a1fd464673a45c3736178917be5) Rework/rename Makefile targets. Bake in image namespace/tag set during build, as part of argo install
 * [3f13f5ca](https://github.com/argoproj/argo-workflows/commit/3f13f5cabe9dc54c7fbaddf7b0cfbcf91c3f26a7) Support for overriding/supplying entrypoint and parameters via argo CLI. Update examples
 * [6f9f2adc](https://github.com/argoproj/argo-workflows/commit/6f9f2adcd017954a72b2b867e6bc2bcba18972af) Support ListOptions in the WorkflowClient. Add flag to delete completed workflows
 * [30d7fba1](https://github.com/argoproj/argo-workflows/commit/30d7fba1205e7f0b4318d6b03064ee647d16ce59) Check Kubernetes version.
 * [a3909273](https://github.com/argoproj/argo-workflows/commit/a3909273c435b23de865089b82b712e4d670a4ff) Give proper error for unamed steps
 * [eed54f57](https://github.com/argoproj/argo-workflows/commit/eed54f5732a61922f6daff9e35073b33c1dc068e) Harden the IsURL check
 * [bfa62afd](https://github.com/argoproj/argo-workflows/commit/bfa62afd857704c53aef32f5ade7df86cf2c0769) Add phase,completed fields to workflow labels. Add startedAt,finishedAt,phase,message to workflow.status
 * [9347619c](https://github.com/argoproj/argo-workflows/commit/9347619c7c125950a9f17acfbd92a1286bca1a57) Create serviceAccount & roleBinding if necessary.
 * [205e5cbc](https://github.com/argoproj/argo-workflows/commit/205e5cbce20a6e5e73c977f1e775671a19bf4434) Introduce 'completed' pod label and label selector so controller can ignore completed pods
 * [199dbcbf](https://github.com/argoproj/argo-workflows/commit/199dbcbf1c3fa2fd452e5c36035d0f0ae8cdde42) 476 jobs list page (#501)
 * [05879294](https://github.com/argoproj/argo-workflows/commit/0587929453ac10d7318a91f2243aece08fe84129) Implement workflow tree tab draft (#494)
 * [a2f034a0](https://github.com/argoproj/argo-workflows/commit/a2f034a063b30b0bb5d9e0f670a8bb38560880b4) Proper error reporting. Add message, startedAt, finishedAt to NodeStatus. Rename status to phase
 * [645fedca](https://github.com/argoproj/argo-workflows/commit/645fedcaf532e052ef0bfc64cb56bfb3307479dd) Support loop step expansion from input parameters and previous step results
 * [75c1c482](https://github.com/argoproj/argo-workflows/commit/75c1c4822b4037176aa6d3702a5cf4eee590c7b7) Help page v2 (#492)
 * [a4af6702](https://github.com/argoproj/argo-workflows/commit/a4af6702d526e775c0aa31ee3612328e5d058c2b) Basic state of  navigation, top-bar, tooltip for UI v2 (#491)
 * [726e9fa0](https://github.com/argoproj/argo-workflows/commit/726e9fa0953fe91eb0401727743a04c8a02668ef) moved the service acct note
 * [3a4cd9c4](https://github.com/argoproj/argo-workflows/commit/3a4cd9c4ba46f586a3d26fbe017d4d3002e6b671) 477 job details page (#488)
 * [8ba7b55c](https://github.com/argoproj/argo-workflows/commit/8ba7b55cb59173ff7470be3451cd38333539b182) Edited the instructions
 * [1e9dbdba](https://github.com/argoproj/argo-workflows/commit/1e9dbdbabbe354f9798162854dd7d6ae4aa8539a) Added influxdb-ci example
 * [bd5c0baa](https://github.com/argoproj/argo-workflows/commit/bd5c0baad83328f13f25ba59e15a5f607d2fb9eb) Added comment for entrypoint field
 * [2fbecdf0](https://github.com/argoproj/argo-workflows/commit/2fbecdf0484a9e3c0d9242bdd7286f83b6e771eb) Argo V2 UI initial commit (#474)
 * [da4ef06e](https://github.com/argoproj/argo-workflows/commit/da4ef06e14c55a3ffc80bcdbd1b637a984f2f0f9) added artifact to ci example
 * [9ce20123](https://github.com/argoproj/argo-workflows/commit/9ce2012303aa30623336f0dde72ad9b80a5409e3) added artifacts
 * [caaa32a6](https://github.com/argoproj/argo-workflows/commit/caaa32a6b3c28c4f5a43514799b26528b55197ee) Minor edit
 * [ae72b583](https://github.com/argoproj/argo-workflows/commit/ae72b583852e43f616d4c021a4e5646235d4c0b4) added more argo/kubectl examples
 * [1db21612](https://github.com/argoproj/argo-workflows/commit/1db21612695a0a9170e265232acc19936b0d7294) merged
 * [8df393ed](https://github.com/argoproj/argo-workflows/commit/8df393ed78d1e4353ee30ba02cec0b12daea7eb0) added 2.0
 * [9e3a51b1](https://github.com/argoproj/argo-workflows/commit/9e3a51b14d78c3622543429a500a7d0367b10787) Update demo.md to have better instructions to restart controller after configuration changes
 * [ba9f9277](https://github.com/argoproj/argo-workflows/commit/ba9f9277a4a9a153a6f5b19862a73364f618e5cd) Add demo markdown file. Delete old demo.txt
 * [d8de40bb](https://github.com/argoproj/argo-workflows/commit/d8de40bb14167f30b17de81d6162d633a62e7a0d) added 2.0
 * [6c617599](https://github.com/argoproj/argo-workflows/commit/6c617599bf4c91ccd3355068967824c1e8d7c107) added 2.0
 * [32af692e](https://github.com/argoproj/argo-workflows/commit/32af692eeec765b13ee3d2b4ede9f5ff45527b4c) added 2.0
 * [802940be](https://github.com/argoproj/argo-workflows/commit/802940be0d4ffd5048dd5307b97af442d82e9a83) added 2.0
 * [1d443415](https://github.com/argoproj/argo-workflows/commit/1d44341553d95ac8192d4a80e178a9d72558829a) added new png
 * [1069af4f](https://github.com/argoproj/argo-workflows/commit/1069af4f3f12bae0e7c33e557ef479203d4adb7c) Support submission of manifests via URL
 * [cc1f0caf](https://github.com/argoproj/argo-workflows/commit/cc1f0caf72bb5e10b7ea087294bf48d0c1215c47) Add recursive coinflip example
 * [90f37ad6](https://github.com/argoproj/argo-workflows/commit/90f37ad63f37500a7b661960ccb8367866054c51) Support configuration of the controller to match specified labels
 * [f9c9673a](https://github.com/argoproj/argo-workflows/commit/f9c9673ac8f7dd84eb249e02358ad13ab0a9849f) Filter non-workflow related pods in the controller's pod watch
 * [9555a472](https://github.com/argoproj/argo-workflows/commit/9555a472ba76d63ed4862c1ef2bb78dbc0d1cac3) Add install notes to support cluster with legacy authentication disabled. Add option to specify service account
 * [837e0a2b](https://github.com/argoproj/argo-workflows/commit/837e0a2b5e254218774579a1a9acfdba8af4aad2) Propogate deletion of controller replicaset/pod during uninstall
 * [5a7fcec0](https://github.com/argoproj/argo-workflows/commit/5a7fcec08b86c8c618c5006a2299aa2d75441fab) Add parameter passing example yaml
 * [2a34709d](https://github.com/argoproj/argo-workflows/commit/2a34709da544c77587438b22f41abd14b3fe004a) Passthrough --namespace flag to `kubectl logs`
 * [3fc6af00](https://github.com/argoproj/argo-workflows/commit/3fc6af0046291e9020db496d072d4d702c02550a) Adding passing parameter example yaml
 * [e275bd5a](https://github.com/argoproj/argo-workflows/commit/e275bd5ac52872f5a940085759683c073fcfa021) Add support for output as parameter
 * [5ee1819c](https://github.com/argoproj/argo-workflows/commit/5ee1819c78e65a2686dbc9fc4d66622cfcbdad9c) Restore and formalize sidecar kill functionality as part of executor
 * [dec97891](https://github.com/argoproj/argo-workflows/commit/dec9789115c0b659c3a838ba1d75ea6ee4dfa350) Proper workflow manifest validation during `argo lint` and `argo submit`
 * [6ab0b610](https://github.com/argoproj/argo-workflows/commit/6ab0b610170ae370bde53c62c38a7e6f707c09eb) Uninstall support via `argo uninstall`
 * [3ba84082](https://github.com/argoproj/argo-workflows/commit/3ba84082a80a55abff9bfcd9a29e5444c89eab61) Adding sidecar container
 * [dba29bd9](https://github.com/argoproj/argo-workflows/commit/dba29bd9dec34aa779d53b68206f4cf414c916bc) Support GCP
 * [f3049105](https://github.com/argoproj/argo-workflows/commit/f3049105664999ec29e955c9ac73c8bd1dfd6730) Proper controller support for running workflows in arbitrary namespaces. Install controller into kube-system namespace by default
 * [ffb3d128](https://github.com/argoproj/argo-workflows/commit/ffb3d128070f2c6961d20ba2ea3c0d64f760b1bb) Add support for controller installation via `argo install` and demo instructions
 * [dcfb2752](https://github.com/argoproj/argo-workflows/commit/dcfb2752172ad8c79da97a5a35895eb62f0d52eb) Add `argo delete` command to delete workflows
 * [8e583afb](https://github.com/argoproj/argo-workflows/commit/8e583afb0a2161d3565651abb1cf7d76d50af861) Add `argo logs` command as a convenience wrapper around `kubectl logs`
 * [368193d5](https://github.com/argoproj/argo-workflows/commit/368193d5002cb2d50b02e397e2b98e09b427227c) Add argo `submit`, `list`, `get`, `lint` commands
 * [8ef7a131](https://github.com/argoproj/argo-workflows/commit/8ef7a131c966c080c8651de7bb08424e501f1c3d) Executor to load script source code as an artifact to main. Remove controller hack
 * [736c5ec6](https://github.com/argoproj/argo-workflows/commit/736c5ec64930df2e25ee7698db9c04044c53ba6c) Annotate pod with outputs. Properly handle tar/gz of artifacts
 * [cd415c9d](https://github.com/argoproj/argo-workflows/commit/cd415c9d56fdd211405c7e5a20789e5f37b049db) Introduce Template.ArchiveLocation to store all related step level artifacts to a job, understood by executor
 * [4241cace](https://github.com/argoproj/argo-workflows/commit/4241cacea3f272146192c90322c9f780f55ef717) Support for saving s3 output artifacts
 * [cd3a3f1e](https://github.com/argoproj/argo-workflows/commit/cd3a3f1e57194fe61634a845ddee0be84b446cde) Bind mount docker.sock to wait container to use `docker wait` and `docker cp`
 * [77d64a66](https://github.com/argoproj/argo-workflows/commit/77d64a66a91e3cd39230714b355374a3d72d5233) Support the case where an input artifact path overlaps with a container volume mount
 * [6a54b31f](https://github.com/argoproj/argo-workflows/commit/6a54b31f3619e26fb5fcb98f897eed5392e546bd) Support for automatic termination for daemoned workflow steps
 * [2435e6f7](https://github.com/argoproj/argo-workflows/commit/2435e6f75a94565217423d244a75170c47115cb8) Track children node IDs in workflow status nodes
 * [227c1961](https://github.com/argoproj/argo-workflows/commit/227c19616fc1ebd1567cf483107d9323e04a6cc7) Initial support for daemon workflow steps (no termination yet)
 * [738b02d2](https://github.com/argoproj/argo-workflows/commit/738b02d20495c06ee63b63261fae2b9e815fe578) Support for git/http input artifacts. hack together wait container logic as a shell script
 * [de71cb5b](https://github.com/argoproj/argo-workflows/commit/de71cb5baccff313d8aa372876f79ab1f8044921) Change according to jesse's comments
 * [621d7ca9](https://github.com/argoproj/argo-workflows/commit/621d7ca98649feaacfdfd3a531f9ed45cd07a86c) Argo Executor init container
 * [efe43927](https://github.com/argoproj/argo-workflows/commit/efe439270af68cd1cef44d7b6874f0ef0f195d9d) Switch representation of parallel steps as a list instead of a map. update examples
 * [56ca947b](https://github.com/argoproj/argo-workflows/commit/56ca947bb57fee22b19f3046873ab771a8637859) Introduce ability to add sidecars to run adjacent to workflow steps
 * [b4d77701](https://github.com/argoproj/argo-workflows/commit/b4d777017c5bdd87db1b004aa8623c213acd3840) Controller support for overlapping artifact path to user specified volume mountPaths
 * [3782bade](https://github.com/argoproj/argo-workflows/commit/3782badead84caff944dbe2bfc3a4f53b3113dd4) Get coinflip example to function
 * [065a8f77](https://github.com/argoproj/argo-workflows/commit/065a8f77f5f84bc4e9f5ddacc3fb630a5ea86d0b) Get python script example to function
 * [8973204a](https://github.com/argoproj/argo-workflows/commit/8973204a5a7f88b91b99f711c7e175be20f6dfc6) Move to list style of inputs and arguments (vs. maps). Reuse artifact datastructure
 * [d9838749](https://github.com/argoproj/argo-workflows/commit/d983874969d40058fa7ca648d5bf17f11ea8c0fb) Improve example yamls
 * [f83b2620](https://github.com/argoproj/argo-workflows/commit/f83b26202d4b896e9ac13e8d93109df3a3bc0c82) Support for volumeClaimTemplates (ephemeral volumes) in workflows
 * [be3ad92e](https://github.com/argoproj/argo-workflows/commit/be3ad92e0c420f22abb306eff33f85b2bbf6bffb) Support for using volumes within multiple steps in a workflow
 * [4b4dc4a3](https://github.com/argoproj/argo-workflows/commit/4b4dc4a315a4b36f077a6bcc9647f04be5a083cb) Copy outputs from pod metadata to workflow node outputs
 * [07f2c965](https://github.com/argoproj/argo-workflows/commit/07f2c9654481d52869df41466aead42220765582) Initial support for conditionals as 'when' field in workflow step
 * [fe639edd](https://github.com/argoproj/argo-workflows/commit/fe639edd6dbbdb4a0405d8449cc2b9aa7bbc9dc0) Controller support for "script" templates (workflow step as code)
 * [a896f03e](https://github.com/argoproj/argo-workflows/commit/a896f03e9daf0bdd466ebe21e42ac5af37dc580c) Add example yamls for proposal for scripting steps
 * [c782e2e1](https://github.com/argoproj/argo-workflows/commit/c782e2e1b8ef9dcd1b2fc30d4d1f834ca2a22c70) Support looping with item maps
 * [7dc58fce](https://github.com/argoproj/argo-workflows/commit/7dc58fce04b45c49df953b90971e3138311c3106) Initial withItems loop support
 * [f3010c1d](https://github.com/argoproj/argo-workflows/commit/f3010c1da94be33712941c7cba0a6820d4ffd762) Support for argument passing and substitution in templates
 * [5e8ba870](https://github.com/argoproj/argo-workflows/commit/5e8ba8701993bb3a1c86317d641ab5c98d69c0bf) Split individual workflow operation logic from controller
 * [63a2c20c](https://github.com/argoproj/argo-workflows/commit/63a2c20c20b1adfc6b3082a341faa72127ab84fd) Introduce sirupsen/logrus logging package
 * [2058342f](https://github.com/argoproj/argo-workflows/commit/2058342f7f8a48337f7dce8e45c22a1fed71babe) Annotate the template used by executor to include destination artifact information
 * [52f8db21](https://github.com/argoproj/argo-workflows/commit/52f8db217581fde487c21dee09821d2c27878d0f) Sync workflow controller configuration from a configmap. Add config validation
 * [d0a1748a](https://github.com/argoproj/argo-workflows/commit/d0a1748afa3c69886a55408d72024fdcecf25c97) Upgrade to golang 1.9.1. Get `make lint` target to function
 * [ac58d832](https://github.com/argoproj/argo-workflows/commit/ac58d8325fc253af0cd00e0d397a5ab60ade5188) Speed up rebuilds from within build container by bind mounting $GOPATH/pkg:/root/go/pkg
 * [71445675](https://github.com/argoproj/argo-workflows/commit/714456753ae81e62f4cf3a563eed20d1b0d1be1a) Add installation manifests. Initial stubs for controller configuration
 * [10372091](https://github.com/argoproj/argo-workflows/commit/103720917b689713ba9b963d00e4578fd6d21fb2) Introduce s3, git, http artifact sources in inputs.artifacts
 * [a68001d3](https://github.com/argoproj/argo-workflows/commit/a68001d31fc4c2d55686a29abe7ace8f0bdf4644) Add debug tools to argoexec image. Remove privileged mode from sidekick. Disable linting
 * [dc530232](https://github.com/argoproj/argo-workflows/commit/dc530232d4595feb0ad01ef45a25bfec23db43a8) Create shared 'input-artifacts' volume and mount between init/main container
 * [6ba84eb5](https://github.com/argoproj/argo-workflows/commit/6ba84eb5285efcacd1f460e11892bce175246799) Expose various pod metadata to argoexec via K8s downward API
 * [1fc079de](https://github.com/argoproj/argo-workflows/commit/1fc079de2fddf992e8d42abf3fe0e556ae7973c2) Add `argo yaml validate` command and `argoexec artifacts load` stub
 * [9125058d](https://github.com/argoproj/argo-workflows/commit/9125058db7c3c45b907c767d040867b3e9c37063) Include scheduling of argoexec (init and sidekick) containers to the user's main
 * [67f8353a](https://github.com/argoproj/argo-workflows/commit/67f8353a045c6fcb713f8b6f534e1caf6fee2be2) Initial workflow operator logic
 * [8137021a](https://github.com/argoproj/argo-workflows/commit/8137021adc20adbb39debbbcdb41332eed7a5451) Reorganize all CLIs into a separate dir. Add stubs for executor and apiserver
 * [74baac71](https://github.com/argoproj/argo-workflows/commit/74baac71754937c4f934be5321a8c24d172a5142) Introduce Argo errors package
 * [37b7de80](https://github.com/argoproj/argo-workflows/commit/37b7de8008ab299e6db3d4616bac2d8af0bcb0fc) Add apiserver skeleton
 * [3ed1dfeb](https://github.com/argoproj/argo-workflows/commit/3ed1dfeb073829d3c4f92b95c9a74118caaec1b4) Initial project structure. CLI and Workflow CRD skeleton

### Contributors

 * Alexander Matyushentsev
 * Anshuman Bhartiya
 * David Kale
 * Ed Lee
 * Edward Lee
 * Javier Castellanos
 * Jesse Suen
 * Matt Hillsdon
 * Rafal
 * Rahul Dhide
 * Rhys Parry
 * Sandeep Bhojwani
 * Shri Javadekar
 * Tianhe Zhang
 * Wojciech Kalemba
 * cyee88
 * gaganapplatix
 * mukulikak

## v0.4.7 (2018-06-07)

 * [e4d0bd39](https://github.com/argoproj/argo-workflows/commit/e4d0bd3926d02fe3e89d6d9b8a02ecbb2db91eff) Take into account number of unavailable replicas to decided if deployment is healthy or not (#270)
 * [18dc82d1](https://github.com/argoproj/argo-workflows/commit/18dc82d14d240485a266350c182560e2d2700ada) Remove hard requirement of initializing OIDC app during server startup (resolves #272)
 * [e720abb5](https://github.com/argoproj/argo-workflows/commit/e720abb58b43f134518ce30239c2a4533effdbc7) Bump version to v0.4.7
 * [a2e9a9ee](https://github.com/argoproj/argo-workflows/commit/a2e9a9ee49052dce05dc9718240dfb8202e5b2c2) Repo names containing underscores were not being accepted (resolves #258)

### Contributors

 * Alexander Matyushentsev
 * Jesse Suen

## v0.4.6 (2018-06-06)

 * [cf377690](https://github.com/argoproj/argo-workflows/commit/cf3776903d8d52af9c656c740601e53947d79609) Retry `argocd app wait` connection errors from EOF watch. Show detailed state changes

### Contributors

 * Jesse Suen

## v0.4.5 (2018-05-31)

 * [3acca509](https://github.com/argoproj/argo-workflows/commit/3acca5095e1bdd028dfd0424abdeb3e5b3036b2d) Add `argocd app unset` command to unset parameter overrides. Bump version to v0.4.5
 * [5a622861](https://github.com/argoproj/argo-workflows/commit/5a622861273da8ccf27bcfd12471b8a377e558e6) Cookie token was not parsed properly when mixed with other site cookies

### Contributors

 * Jesse Suen

## v0.4.4 (2018-05-30)

 * [5452aff0](https://github.com/argoproj/argo-workflows/commit/5452aff0bebdbba3990f1cc2e300f6f37f634b8b) Add ability to show parameters and overrides in CLI (resolves #240) (#247)
 * [0f4f1262](https://github.com/argoproj/argo-workflows/commit/0f4f1262af8837748da06fdcc9accf4ced273dfd) Add Events API endpoint (#237)
 * [4e7f68cc](https://github.com/argoproj/argo-workflows/commit/4e7f68ccbae9b362178bcdaafc1c0c29fcc1ef19) Update version to 0.4.4
 * [96c05bab](https://github.com/argoproj/argo-workflows/commit/96c05babe026b998fb80033c76594585b869c8a2) Issue #238 - add upsert flag to 'argocd app create' command (#245)
 * [6b78cddb](https://github.com/argoproj/argo-workflows/commit/6b78cddb1921dad6c3f0fe53c85c51711ba8b2de) Add repo browsing endpoint (#229)
 * [12596ff9](https://github.com/argoproj/argo-workflows/commit/12596ff9360366afbadfcd366586318b74e410ca) Issue #233 - Controller does not persist rollback operation result (#234)
 * [a240f1b2](https://github.com/argoproj/argo-workflows/commit/a240f1b2b9e7d870d556fb4420016852a733b9c5) Bump version to 0.5.0
 * [f6da1967](https://github.com/argoproj/argo-workflows/commit/f6da19672e6388ae481dc72b32703973c0ebe921) Support subscribing to settings updates and auto-restart of dex and API server (resolves #174) (#227)
 * [e81d30be](https://github.com/argoproj/argo-workflows/commit/e81d30be9b378312d626a3b5034f2f4d2d1f70d5) Update getting_started.md to point to v0.4.3
 * [13b090e3](https://github.com/argoproj/argo-workflows/commit/13b090e3bd96dc984bc266c49c536511dff793d1) Issue #147 - App sync frequently fails due to concurrent app modification (#226)
 * [d0479e6d](https://github.com/argoproj/argo-workflows/commit/d0479e6ddcba5fe66ed2137935bcec51dedb4f27) Issue # 223 - Remove app finalizers during e2e fixture teardown (#225)
 * [14328270](https://github.com/argoproj/argo-workflows/commit/1432827006855aa526966de93c88551ce049b5ce) Add error fields to cluster/repo, shell output (#200)

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Jesse Suen

## v0.4.3 (2018-05-21)

 * [89bf4eac](https://github.com/argoproj/argo-workflows/commit/89bf4eac7105ced9279203b7085f07ac76a13ee5) Bump version to 0.4.3
 * [07aac0bd](https://github.com/argoproj/argo-workflows/commit/07aac0bdae285201e36e73b88bd16f2318a04be8) Move local branch deletion as part of git Reset() (resolves #185) (#222)
 * [61220b8d](https://github.com/argoproj/argo-workflows/commit/61220b8d0d5b217866e5c2fa6f6d739eea234225) Fix exit code for app wait (#219)

### Contributors

 * Andrew Merenbach
 * Jesse Suen

## v0.4.2 (2018-05-21)

 * [4e470aaf](https://github.com/argoproj/argo-workflows/commit/4e470aaf096b7acadf646063781af811168276ea) Remove context name prompt during login. (#218)
 * [76922b62](https://github.com/argoproj/argo-workflows/commit/76922b620b295897f8f86416cea1b41d558a0d24) Update version to 0.4.2

### Contributors

 * Jesse Suen

## v0.4.1 (2018-05-18)

 * [ac0f623e](https://github.com/argoproj/argo-workflows/commit/ac0f623eda0cd7d6adb5f8be8655a22e910a120d) Add `argocd app wait` command (#216)
 * [afd54508](https://github.com/argoproj/argo-workflows/commit/afd5450882960f4f723197e56ea7c67dc65b8d10) Bump version to v0.4.1
 * [c17266fc](https://github.com/argoproj/argo-workflows/commit/c17266fc2173246775cecfb6625d6d60eac2d2b8) Add documentation on how to configure SSO and Webhooks
 * [f62c8254](https://github.com/argoproj/argo-workflows/commit/f62c825495211a738d11f9e95e1aec59a5031be0) Manifest endpoint (#207)
 * [45f44dd4](https://github.com/argoproj/argo-workflows/commit/45f44dd4be375002300f96386ffb3383c2119ff8) Add v0.4.0 changelog
 * [9c0daebf](https://github.com/argoproj/argo-workflows/commit/9c0daebfe088a1ac5145417df14d11769f266e82) Fix diff falsely reporting OutOfSync due to namespace/annotation defaulting
 * [f2a0ca56](https://github.com/argoproj/argo-workflows/commit/f2a0ca560971680e21b20645d62462a29ac25721) Add intelligence in diff libray to perform three-way diff from last-applied-configuration annotation (resolves #199)
 * [e04d3158](https://github.com/argoproj/argo-workflows/commit/e04d315853ec9ed25d8359136d6141e821fae5e1) Issue #118 - app delete should be done through controller using finalizers (#206)
 * [daec6976](https://github.com/argoproj/argo-workflows/commit/daec697658352b9a607f5d4cc777eae24db0ed33) Update ksonnet to v0.10.2 (resolves #208)
 * [7ad56707](https://github.com/argoproj/argo-workflows/commit/7ad56707102a31d64214f8fb47ab840fd2550826) Make sure api server started during fixture setup (#209)
 * [80364233](https://github.com/argoproj/argo-workflows/commit/8036423373e79b48a52a34bd524f1cdf8bf2fd46) Implement App management and repo management e2e tests (#205)
 * [8039228a](https://github.com/argoproj/argo-workflows/commit/8039228a9d31a445461231de172425e911e9eaea) Add last update time to operation status, fix operation status patching (#204)
 * [b1103af4](https://github.com/argoproj/argo-workflows/commit/b1103af4290e6e6134f2d4f62df32f90aa8448d5) Rename recent deployments to history (#201)
 * [d67ad5ac](https://github.com/argoproj/argo-workflows/commit/d67ad5acfd598712c153f14a1c7946759dbc733c) Add connect timeouts when interacting with SSH git repos (resolves #131) (#203)
 * [c9df9c17](https://github.com/argoproj/argo-workflows/commit/c9df9c17b77688ac5725a9fa00222006a5fd9f4f) Default Spec.Source.TargetRevision to HEAD server-side if unspecified (issue #190)
 * [8fa46b02](https://github.com/argoproj/argo-workflows/commit/8fa46b02b0784a9922aa93be5896e65732a1729d) Remove SyncPolicy (issue #190)
 * [92c48133](https://github.com/argoproj/argo-workflows/commit/92c481330d655697a6630813b63617de6789f403) App creation was not defaulting to server and namespace defined in app.yaml
 * [2664db3e](https://github.com/argoproj/argo-workflows/commit/2664db3e4072b96176d286f7a91f03d08e5cc715) Refactor application controller sync/apply loop (#202)
 * [6b554e5f](https://github.com/argoproj/argo-workflows/commit/6b554e5f4efa3473be217ebbcaf89acb22ded628) Add 0.3.0 to 0.4.0 migration utility (#186)
 * [2bc0dff1](https://github.com/argoproj/argo-workflows/commit/2bc0dff1359031cc335769c3a742987cb1c4e7ba) Issue #146 - Render health status information in 'app list' and 'app get' commands (#198)
 * [c61795f7](https://github.com/argoproj/argo-workflows/commit/c61795f71afd5705d75a4377c9265023aa7cec2c) Add 'database' library for CRUD operations against repos and clusters. Redact sensitive information (#196)
 * [a8a7491b](https://github.com/argoproj/argo-workflows/commit/a8a7491bf0b0534bbf63c08291a4966aa81403fa) Handle potential panic when `argo install settings` run against an empty configmap

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Jesse Suen

## v0.4.0-alpha1 (2018-05-11)


### Contributors


## v0.4.0 (2018-05-17)

 * [9c0daebf](https://github.com/argoproj/argo-workflows/commit/9c0daebfe088a1ac5145417df14d11769f266e82) Fix diff falsely reporting OutOfSync due to namespace/annotation defaulting
 * [f2a0ca56](https://github.com/argoproj/argo-workflows/commit/f2a0ca560971680e21b20645d62462a29ac25721) Add intelligence in diff libray to perform three-way diff from last-applied-configuration annotation (resolves #199)
 * [e04d3158](https://github.com/argoproj/argo-workflows/commit/e04d315853ec9ed25d8359136d6141e821fae5e1) Issue #118 - app delete should be done through controller using finalizers (#206)
 * [daec6976](https://github.com/argoproj/argo-workflows/commit/daec697658352b9a607f5d4cc777eae24db0ed33) Update ksonnet to v0.10.2 (resolves #208)
 * [7ad56707](https://github.com/argoproj/argo-workflows/commit/7ad56707102a31d64214f8fb47ab840fd2550826) Make sure api server started during fixture setup (#209)
 * [80364233](https://github.com/argoproj/argo-workflows/commit/8036423373e79b48a52a34bd524f1cdf8bf2fd46) Implement App management and repo management e2e tests (#205)
 * [8039228a](https://github.com/argoproj/argo-workflows/commit/8039228a9d31a445461231de172425e911e9eaea) Add last update time to operation status, fix operation status patching (#204)
 * [b1103af4](https://github.com/argoproj/argo-workflows/commit/b1103af4290e6e6134f2d4f62df32f90aa8448d5) Rename recent deployments to history (#201)
 * [d67ad5ac](https://github.com/argoproj/argo-workflows/commit/d67ad5acfd598712c153f14a1c7946759dbc733c) Add connect timeouts when interacting with SSH git repos (resolves #131) (#203)
 * [c9df9c17](https://github.com/argoproj/argo-workflows/commit/c9df9c17b77688ac5725a9fa00222006a5fd9f4f) Default Spec.Source.TargetRevision to HEAD server-side if unspecified (issue #190)
 * [8fa46b02](https://github.com/argoproj/argo-workflows/commit/8fa46b02b0784a9922aa93be5896e65732a1729d) Remove SyncPolicy (issue #190)
 * [92c48133](https://github.com/argoproj/argo-workflows/commit/92c481330d655697a6630813b63617de6789f403) App creation was not defaulting to server and namespace defined in app.yaml
 * [2664db3e](https://github.com/argoproj/argo-workflows/commit/2664db3e4072b96176d286f7a91f03d08e5cc715) Refactor application controller sync/apply loop (#202)
 * [6b554e5f](https://github.com/argoproj/argo-workflows/commit/6b554e5f4efa3473be217ebbcaf89acb22ded628) Add 0.3.0 to 0.4.0 migration utility (#186)
 * [2bc0dff1](https://github.com/argoproj/argo-workflows/commit/2bc0dff1359031cc335769c3a742987cb1c4e7ba) Issue #146 - Render health status information in 'app list' and 'app get' commands (#198)
 * [c61795f7](https://github.com/argoproj/argo-workflows/commit/c61795f71afd5705d75a4377c9265023aa7cec2c) Add 'database' library for CRUD operations against repos and clusters. Redact sensitive information (#196)
 * [a8a7491b](https://github.com/argoproj/argo-workflows/commit/a8a7491bf0b0534bbf63c08291a4966aa81403fa) Handle potential panic when `argo install settings` run against an empty configmap
 * [d1c7c4fc](https://github.com/argoproj/argo-workflows/commit/d1c7c4fcafb66bac6553247d16a03863d25910e6) Issue #187 - implement `argo settings install` command (#193)
 * [3dbbcf89](https://github.com/argoproj/argo-workflows/commit/3dbbcf891897f3c3889189016ae1f3fabcddca1f) Move sync logic to contoller (#180)
 * [0cfd1ad0](https://github.com/argoproj/argo-workflows/commit/0cfd1ad05fe8ec0c78dfd85ba0f91027522dfe70) Update feature list with SSO and Webhook integration
 * [bfa4e233](https://github.com/argoproj/argo-workflows/commit/bfa4e233b72ef2863d1bfb010ba95fad519a9c43) cli will look to spec.destination.server and namespace when displaying apps
 * [dc662da3](https://github.com/argoproj/argo-workflows/commit/dc662da3d605bd7189ce6c06b0dbc1661d4bf2fb) Support OAuth2 login flow from CLI (resolves #172) (#181)
 * [4107d242](https://github.com/argoproj/argo-workflows/commit/4107d2422bb6331833f360f2cab01eb24500e173) Fix linting errors
 * [b83eac5d](https://github.com/argoproj/argo-workflows/commit/b83eac5dc2f9c026ad07258e4c01d5217e2992fe) Make ApplicationSpec.Destination non-optional, non-pointer (#177)
 * [bb51837c](https://github.com/argoproj/argo-workflows/commit/bb51837c56a82e486d68a350b3b4397ff930ec37) Do not delete namespace or CRD during uninstall unless explicitly stated (resolves #167) (#173)
 * [5bbb4fe1](https://github.com/argoproj/argo-workflows/commit/5bbb4fe1a131ed3380a857af3db5e9d708f3b7f6) Cache kubernetes API resource discovery (resolves #170) (#176)
 * [b5c20e9b](https://github.com/argoproj/argo-workflows/commit/b5c20e9b46ea19b63f3f894d784d5a25b97f0ebb) Trim spaces server-side in GitHub usernames (#171)
 * [1e1ab636](https://github.com/argoproj/argo-workflows/commit/1e1ab636e042da4d5f1ee4e47a01f301d6a458a7) Don't fail when new app has same spec as old (#168)
 * [73485538](https://github.com/argoproj/argo-workflows/commit/7348553897af89b9c4366f2d445dd2d96fe4d655) Improve CI build stability
 * [5f65a512](https://github.com/argoproj/argo-workflows/commit/5f65a5128a3fa42f12a60908eee3fa5d11624305) Introduce caching layer to repo server to improve query response times (#165)
 * [d9c12e72](https://github.com/argoproj/argo-workflows/commit/d9c12e72719dffaf6951b5fb71e4bae8a8ddda0d) Issue #146 - ArgoCD applications should have a rolled up health status (#164)
 * [fb2d6b4a](https://github.com/argoproj/argo-workflows/commit/fb2d6b4afff1ba66880691d188c284a77f6ac99e) Refactor repo server and git client (#163)
 * [3f4ec0ab](https://github.com/argoproj/argo-workflows/commit/3f4ec0ab2263038ba91d3b594b2188fc108fc8d7) Expand Git repo URL normalization (#162)
 * [ac938fe8](https://github.com/argoproj/argo-workflows/commit/ac938fe8a3af46f7aac07d607bfdd0a375e74103) Add GitHub webhook handling to fast-track controller application reprocessing (#160)
 * [dc1e8796](https://github.com/argoproj/argo-workflows/commit/dc1e8796fb40013a7980e8bc18f8b2545c6e6cca) Disable authentication for settings service
 * [8c5d59c6](https://github.com/argoproj/argo-workflows/commit/8c5d59c60c679ab6d35f8a6e51337c586dc4fdde) Issue #157 - If argocd token is expired server should return 401 instead of 500 (#158)

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Jesse Suen

## v0.3.3 (2018-05-03)

 * [13558b7c](https://github.com/argoproj/argo-workflows/commit/13558b7ce8d7bd9f8707a6a18f45af8662b1c60d) Revert change to redact credentials since logic is reused by controller
 * [3b2b3dac](https://github.com/argoproj/argo-workflows/commit/3b2b3dacf50f9b51dde08f1d1e1e757ed30c24a4) Update version
 * [1b2f8999](https://github.com/argoproj/argo-workflows/commit/1b2f89995c970eb9fb5fe7bce4ac0253bddb9d7d) Issue #155 - Application update failes due to concurrent access (#156)
 * [0479fcdf](https://github.com/argoproj/argo-workflows/commit/0479fcdf82b1719fd97767ea74509063e9308b0a) Add settings endpoint so frontend can show/hide SSO login button. Rename config to settings (#153)
 * [a0446546](https://github.com/argoproj/argo-workflows/commit/a04465466dfa4dc039222732cd9dbb84f9fdb3dd) Add workflow for blue-green deployments (#148)
 * [670921df](https://github.com/argoproj/argo-workflows/commit/670921df902855b209094b59f32ce3e051a847fd) SSO Support (#152)
 * [18f7e17d](https://github.com/argoproj/argo-workflows/commit/18f7e17d7a200a0dd1c8447acc2815981c0093a6) Added OWNERS file
 * [a2aede04](https://github.com/argoproj/argo-workflows/commit/a2aede04412380b7853041fbce6dd6d377e483e9) Redact sensitive repo/cluster information upon retrieval (#150)

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Edward Lee
 * Jesse Suen

## v0.3.2 (2018-05-01)

 * [1d876c77](https://github.com/argoproj/argo-workflows/commit/1d876c77290bbfc830790bff977c8a65a0432e0c) Fix compilation error
 * [70465a05](https://github.com/argoproj/argo-workflows/commit/70465a0520410cd4466d1feb4eb9baac98e94688) Issue #147 - Use patch to update recentDeployments field (#149)
 * [3c984571](https://github.com/argoproj/argo-workflows/commit/3c9845719f643948a5f1be83ee7039e7f33b8c65)  Issue #139 - Application sync should delete 'unexpected' resources (#144)
 * [a36cc894](https://github.com/argoproj/argo-workflows/commit/a36cc8946c8479745f63c24df4a9289d70f0a773) Issue #136 - Use custom formatter to get desired state of deployment and service (#145)
 * [9567b539](https://github.com/argoproj/argo-workflows/commit/9567b539d1d2fcb9535cdb7c91f9060a7ac06d8f) Improve comparator to fall back to looking up a resource by name
 * [fdf9515d](https://github.com/argoproj/argo-workflows/commit/fdf9515de2826d53f8b138f99c8896fdfa5f919e) Refactor git library: * store credentials in files (instead of encoded in URL) to prevent leakage during git errors * fix issue where HEAD would not track updates from origin/HEAD (resolves #133) * refactor git library to promote code reuse, and remove shell invocations
 * [b3202384](https://github.com/argoproj/argo-workflows/commit/b320238487c339186f1e0be5e1bfbb35fa0036a4) ksonnet util was not locating a ksonnet app dir correctly
 * [7872a604](https://github.com/argoproj/argo-workflows/commit/7872a60499ebbda01cd31f859eba8e7209f16b9c) Update ksonnet to v0.10.1
 * [5fea3846](https://github.com/argoproj/argo-workflows/commit/5fea3846d1c09bca9d0e68f1975598b29b5beb91) Adding clusters should always go through argocd-manager service account creation
 * [86a4e0ba](https://github.com/argoproj/argo-workflows/commit/86a4e0baaa8932daeba38ac74535497e773f24b9) RoleBindings do not need to specify service account namespace in subject
 * [917f1df2](https://github.com/argoproj/argo-workflows/commit/917f1df250013ec462f0108bfb85b54cb56c53c4) Populated 'unexpected' resources while comparing target and live states (#137)
 * [11260f24](https://github.com/argoproj/argo-workflows/commit/11260f24763dab2e2364d8cb4c5789ac046666a8) Don't ask for user credentials if username and password are specified as arguments (#129)
 * [38d20d0f](https://github.com/argoproj/argo-workflows/commit/38d20d0f0406e354c6ca4d9f2776cbb8a322473c) Add `argocd ctx` command for switching between contexts. Better CLI descriptions (resolves #103)
 * [938f40e8](https://github.com/argoproj/argo-workflows/commit/938f40e817a44eb1c806102dc90593af2adb5d88) Prompting for repo credentials was accepting newline as username
 * [5f9c8b86](https://github.com/argoproj/argo-workflows/commit/5f9c8b862edbcba5d079621f0c4bba0e942add9b) Error properly when server address is unspecified (resolves #128)
 * [d96d67bb](https://github.com/argoproj/argo-workflows/commit/d96d67bb9a4eae425346298d513a1cf52e89da62) Generate a temporary kubeconfig instead of using kubectl flags when applying resources
 * [19c3b876](https://github.com/argoproj/argo-workflows/commit/19c3b876767571257fbadad35971d8f6eecd2d74) Bump version to 0.4.0. `argocd app sync --dry-run` was incorrectly appending items to history (resolves #127)

### Contributors

 * Alexander Matyushentsev
 * Jesse Suen

## v0.3.1 (2018-04-24)

 * [7d08ab4e](https://github.com/argoproj/argo-workflows/commit/7d08ab4e2b5028657c6536dc9007ac5b9da13b8d) Bump version to v0.3.1
 * [efea09d2](https://github.com/argoproj/argo-workflows/commit/efea09d2165e35b6b2176fd0ff6f5fcd0c4699e4) Fix linting issue in `app rollback`
 * [2adaef54](https://github.com/argoproj/argo-workflows/commit/2adaef547be26b9911676ff048b0ea38d8e87df2) Introduce `argocd app history` and `argocd app rollback` CLI commands (resolves #125)
 * [d71bbf0d](https://github.com/argoproj/argo-workflows/commit/d71bbf0d9a00046622498200754f7ae6639edfc4) Allow overriding server or namespace separately (#126)
 * [36b3b2b8](https://github.com/argoproj/argo-workflows/commit/36b3b2b8532142d50c3ada0d8d3cb2328c8a32e4) Switch to gogo/protobuf for golang code generation in order to use gogo extensions
 * [63dafa08](https://github.com/argoproj/argo-workflows/commit/63dafa08ccdef6141f83f26157bd32192c62f052) Issue #110 - Rollback ignores parameter overrides (#117)
 * [afddbbe8](https://github.com/argoproj/argo-workflows/commit/afddbbe875863c8d33a85d2d2874f0703153c195) Issue #123 - Create .argocd directory before saving config file (#124)
 * [34811caf](https://github.com/argoproj/argo-workflows/commit/34811cafca3df45952677407ce5458d50f23e0fd) Update download instructions to getting started

### Contributors

 * Alexander Matyushentsev
 * Jesse Suen

## v0.3.0 (2018-04-23)

 * [8a285116](https://github.com/argoproj/argo-workflows/commit/8a2851169c84741d774818ec8943a444d523f082) Enable auth by default. Decrease app resync period from 10m to 3m
 * [1a85a2d8](https://github.com/argoproj/argo-workflows/commit/1a85a2d8051ee64ad16b0487e2a3d14cf4fb01e6) Bump version file to 0.3.0. Add release target and cli-linux/darwin targets
 * [cf2d00e1](https://github.com/argoproj/argo-workflows/commit/cf2d00e1e04219ed99195488740189fbd6af997d) Add ability to set a parameter override from the CLI (`argo app set -p`)
 * [266c948a](https://github.com/argoproj/argo-workflows/commit/266c948adddab715ba2c60f082bd7e37aec6f814) Add documentation about ArgoCD tracking strategies
 * [dd564ee9](https://github.com/argoproj/argo-workflows/commit/dd564ee9dd483f3e19bceafd30e5842a005e04f1) Introduce `app set` command for updating an app (resolves #116)
 * [b9d48cab](https://github.com/argoproj/argo-workflows/commit/b9d48cabb99e336ea06e1a7af56f2e74e740a9cf) Add ability to set the tracking revision during app creation
 * [276e0674](https://github.com/argoproj/argo-workflows/commit/276e0674c37a975d903404b3e3bf747b7e99a787) Deployment of resources is performed using `kubectl apply` (resolves #106)
 * [f3c4a693](https://github.com/argoproj/argo-workflows/commit/f3c4a6932730c53ae1cf9de2df9e62c89e54ea53) Add watch verb to controller role
 * [1c60a698](https://github.com/argoproj/argo-workflows/commit/1c60a69866dae95c7bf4a0f912292a5a6714611f) Rename `argocd app add/rm` to `argocd app create/delete` (resolves #114)
 * [050f937a](https://github.com/argoproj/argo-workflows/commit/050f937a2409111194f6c4ff7cc75a3f2ed3fa0b) Update ksonnet to v0.10.0-alpha.3
 * [b24e4782](https://github.com/argoproj/argo-workflows/commit/b24e478224a359c883425f2640f4327f29b3ab80) Add application validation
 * [e34380ed](https://github.com/argoproj/argo-workflows/commit/e34380ed765bc8b802d60ab30c25a1389ebd33a8) Expose port 443 to proxy to port 8080 (#113)
 * [338a1b82](https://github.com/argoproj/argo-workflows/commit/338a1b826fd597eafd0a654ca424a0c90b4647e0) `argo login` was not able to properly update boolean connection flags (insecure/plaintext)
 * [b87c63c8](https://github.com/argoproj/argo-workflows/commit/b87c63c897dc0e7c11b311d9f6de6f6436186aeb) Re-add workaround for ksonnet bug
 * [f6ed150b](https://github.com/argoproj/argo-workflows/commit/f6ed150bb7e9f50854fe4f7e4d00cc7ab1ccd581) Issue #108 - App controller incorrectly report that app is out of sync (#109)
 * [d5c683bc](https://github.com/argoproj/argo-workflows/commit/d5c683bc76f6e3eb1b5570b50d795b387481087f) Add syncPolicy field to application CRD (#107)
 * [3ac95f3f](https://github.com/argoproj/argo-workflows/commit/3ac95f3f84c6b85aa8e0ff0c9c68e2ccbbaa8875) Fix null pointer error in controller (#105)
 * [3be872ad](https://github.com/argoproj/argo-workflows/commit/3be872ad32891cc7628b3717bff31deb687a556f) Rework local config to support multiple servers/credentials
 * [80964a79](https://github.com/argoproj/argo-workflows/commit/80964a79b2b8cd1383eb1cbf03eddb608c13b771) Set session cookies, errors appropriately (#100)
 * [e719035e](https://github.com/argoproj/argo-workflows/commit/e719035ea5ba3d08bc4118151989071befb127ac) Allow ignoring recource deletion related errors while deleting application (#98)
 * [f2bcf63b](https://github.com/argoproj/argo-workflows/commit/f2bcf63b26257bb83220d3a94ddbb394b591b659) Fix linting breakage in session mock from recent changes to session interface
 * [2c9843f1](https://github.com/argoproj/argo-workflows/commit/2c9843f1a083ce41ec3fa9aebf14fb5028a17765) Update ksonnet to v0.10.0-alpha.2
 * [0560406d](https://github.com/argoproj/argo-workflows/commit/0560406d815f7012f4c45bda8d2a3d940457bd3a) Add server auth cookies (#96)
 * [db8083c6](https://github.com/argoproj/argo-workflows/commit/db8083c6573ba4a514bbad11d73f5e65e9ed06a6) Lowercase repo names before using in secret (#94)
 * [fcc9f50b](https://github.com/argoproj/argo-workflows/commit/fcc9f50b3fe35f71ab2ead6181517bf16e06ac7f) Fix issue preventing uppercased repo and cluster URLs (resolves #81)
 * [c1ffbad8](https://github.com/argoproj/argo-workflows/commit/c1ffbad8d89ed0aad0ce680463fe38297afb09b8) Support manual token use for CLI commands (#90)
 * [d7cdb1a5](https://github.com/argoproj/argo-workflows/commit/d7cdb1a5af3aae50d67ff4d2346375ffe3bbf1af) Convert Kubernetes errors to gRPC errors (#89)
 * [6c41ce5e](https://github.com/argoproj/argo-workflows/commit/6c41ce5e086822529a37002878ab780778df26b9) Add session gateway (#84)
 * [685a814f](https://github.com/argoproj/argo-workflows/commit/685a814f3870237c560c83724af5fc214af158b8) Add `argocd login` command (#82)
 * [06b64047](https://github.com/argoproj/argo-workflows/commit/06b64047a4b5e6d7728ac6ca2eac03327f42ca37) Issue #69 - Auto-sync option in application CRD instance (#83)
 * [8a90b324](https://github.com/argoproj/argo-workflows/commit/8a90b324461ecc35a6d94296154e5aaa86e0adc5) Show more relevant information in `argocd cluster add`
 * [7e47b1eb](https://github.com/argoproj/argo-workflows/commit/7e47b1ebae32b01b927c76c120cdab7be8084d13) TLS support. HTTP/HTTPS/gRPC all serving on single port
 * [150b51a3](https://github.com/argoproj/argo-workflows/commit/150b51a3ac43cac00aae886fe2c3ac5b1fb0a588) Fix linter warning
 * [0002f8db](https://github.com/argoproj/argo-workflows/commit/0002f8db9e9e96f2601ee4bd005864cd88e0ee50) Issue #75 - Implement delete pod API
 * [59ed50d2](https://github.com/argoproj/argo-workflows/commit/59ed50d230d86946ed8a1d881771f24897dba305) Issue #74 - Implement stream logs API
 * [820b4bac](https://github.com/argoproj/argo-workflows/commit/820b4bac1afc7ce5c42779c80fc36fbe5fbf9893) Remove obsolete pods api
 * [19c5ecdb](https://github.com/argoproj/argo-workflows/commit/19c5ecdbfabd83a83f2b83a34b0b66b984c5cfa8) Check app label on client side before deleting app resource
 * [66b0702c](https://github.com/argoproj/argo-workflows/commit/66b0702c2437421a414b72b29d1322ad49be7884) Issue #65 - Delete all the kube object once app is removed
 * [5b5dc0ef](https://github.com/argoproj/argo-workflows/commit/5b5dc0efc40637279d070cf5eb004a9378d25433) Issue #67 - Application controller should persist ksonnet app parameters in app CRD (#73)
 * [0febf051](https://github.com/argoproj/argo-workflows/commit/0febf0516005bbfd5de455d7a32c47b94bd1ca60) Issue #67 - Persist resources tree in application CRD (#68)
 * [ee924bda](https://github.com/argoproj/argo-workflows/commit/ee924bda6ecdc1076db564252d95d5b1e9a0f365) Update ksonnet binary in image to ks tip. Begin using ksonnet as library instead of parsing stdout
 * [ecfe571e](https://github.com/argoproj/argo-workflows/commit/ecfe571e758228f8e63c98c9d529941be31a0a20) update ksonnet dependency to tip. override some of ksonnet's dependencies
 * [173ecd93](https://github.com/argoproj/argo-workflows/commit/173ecd9397a6a91c85931675874b0a9550be1346) Installer and settings management refactoring:
 * [ba3db35b](https://github.com/argoproj/argo-workflows/commit/ba3db35ba08e8b1c625c94107023f3c15235636a) Add authentication endpoints (#61)
 * [074053da](https://github.com/argoproj/argo-workflows/commit/074053dac77c67913a33f1cc894beccb9cc0553d) Update go-grpc-middleware version (#62)
 * [6bc98f91](https://github.com/argoproj/argo-workflows/commit/6bc98f91b146ab56cd9cbdd66d756cb281730c59) Add JWT support (#60)

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Jesse Suen

## v0.2.0 (2018-03-28)

 * [59dbe8d7](https://github.com/argoproj/argo-workflows/commit/59dbe8d7eace6f9b82fda59a0590f0f3e24cc514) Maintain list of recent deployments in app CRD (#59)
 * [6d793617](https://github.com/argoproj/argo-workflows/commit/6d793617399a2b1abed8e6cb561115f9311eafae) Issue #57 - Add configmaps into argocd server role (#58)
 * [e1c7f9d6](https://github.com/argoproj/argo-workflows/commit/e1c7f9d6f86f4a489c79e921f38f15ba02de6472) Fix deleting resources which do not support 'deletecollection' method but support 'delete' (#56)
 * [5febea22](https://github.com/argoproj/argo-workflows/commit/5febea22354eb8b6b56e22096a3cddefcded34ad) Argo server should not fail if configmap name is not provided or config map does not exist (#55)
 * [d093c8c3](https://github.com/argoproj/argo-workflows/commit/d093c8c3a17d51a83514c7a355239409409d1e78) Add password hashing (#51)
 * [10a8d521](https://github.com/argoproj/argo-workflows/commit/10a8d521ef5b21ee139128dad33e0ad160cc56fd) Add application source and component parameters into recentDeployment field of application CRD (#53)
 * [234ace17](https://github.com/argoproj/argo-workflows/commit/234ace173ed1b8de4ca1010e9b583cdb5ce6bf40) Replace ephemeral environments with override parameters (#52)
 * [817b13cc](https://github.com/argoproj/argo-workflows/commit/817b13ccbed93f41a851d2dd71040e2e2bc975a0) Add license and copyright. #49
 * [b1682cc4](https://github.com/argoproj/argo-workflows/commit/b1682cc44be8069642d7d0a0edab0137e69a15c7) Add install configmap override flag (#47)
 * [74797a2a](https://github.com/argoproj/argo-workflows/commit/74797a2ac80ca0375a02c4a8b38a972bfa19c9f2) Delete child dependents while deleting app resources (#48)
 * [ca570c7a](https://github.com/argoproj/argo-workflows/commit/ca570c7aeeb70df1c7d4ec75b1571038142ef714) Use ksonnet release version and fix app copy command (#46)
 * [92b7c6b5](https://github.com/argoproj/argo-workflows/commit/92b7c6b5f8773f1504f12245d5f77854621d2c2c) Disable strict host key checking while cloning repo in repo-server (#45)
 * [4884c20d](https://github.com/argoproj/argo-workflows/commit/4884c20d2bfaaf65c5e6a222d22fb684c9f72788) Issue #43 - Don't setup RBAC resources for clusters with basic authentication (#44)
 * [363b9b35](https://github.com/argoproj/argo-workflows/commit/363b9b352c1de1e6a84d516e6812ed6fdac3f013) Don't overwrite application status in tryRefreshAppStatus (#42)
 * [5c062bd3](https://github.com/argoproj/argo-workflows/commit/5c062bd3e51bab46979040c79795c4872c2c0d2f) Support deploying/destroying ephemeral environments (#40)
 * [98754c7f](https://github.com/argoproj/argo-workflows/commit/98754c7fe1cbfc2f39890c976949d1540af75d9c) Persist parameters during deployment (Sync) (#39)
 * [3927cc07](https://github.com/argoproj/argo-workflows/commit/3927cc0799456518f889dd9c53a40a2c746d546e) Add new dependency to CONTRIBUTING.md (#38)
 * [611b0e48](https://github.com/argoproj/argo-workflows/commit/611b0e48d7be40f6cb1b30d3e3da180a443e872f) Issue #34 - Support ssh git URLs and ssh key authentication (#37)
 * [0368c2ea](https://github.com/argoproj/argo-workflows/commit/0368c2eadfe34a979973e0b40b6cb4c288e55f38) Allow use of public repos without prior registration (#36)
 * [e7e3c509](https://github.com/argoproj/argo-workflows/commit/e7e3c5095c0a1b4312993a234aceb0b90d69f90e) Support -f/--file flag in `argocd app add` (#35)
 * [d256256d](https://github.com/argoproj/argo-workflows/commit/d256256defbf6dcc733424df9374a2dc32069875) Update CONTRIBUTING.md (#32)

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Edward Lee

