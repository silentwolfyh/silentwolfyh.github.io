解决方案：参考Study.md

```
(xiaohui)  yuhui@yuhuideMacBook-Pro  ~/PycharmProjects/ngn_code/ngnlab-website-admin-master  sudo npm install hexo --save

up to date, audited 941 packages in 3s

42 packages are looking for funding
  run `npm fund` for details

11 vulnerabilities (2 low, 1 moderate, 8 high)

To address issues that do not require attention, run:
  npm audit fix

Some issues need review, and may require choosing
a different dependency.

Run `npm audit` for details.


#######################################################  分界线  #################################################################

(xiaohui)  ✘ yuhui@yuhuideMacBook-Pro  ~/PycharmProjects/ngn_code/ngnlab-website-admin-master  sudo npm audit fix

up to date, audited 941 packages in 2s

42 packages are looking for funding
  run `npm fund` for details

# npm audit report

braces  <=2.3.0
Regular Expression Denial of Service in braces - https://github.com/advisories/GHSA-g95f-p29q-9xw4
Regular Expression Denial of Service (ReDoS) in braces - https://github.com/advisories/GHSA-cwfw-4gq5-mrqx
No fix available
node_modules/hexo-prism-plugin/node_modules/braces
  micromatch  0.2.0 - 2.3.11
  Depends on vulnerable versions of braces
  Depends on vulnerable versions of parse-glob
  node_modules/hexo-prism-plugin/node_modules/micromatch
    anymatch  1.2.0 - 1.3.2
    Depends on vulnerable versions of micromatch
    node_modules/hexo-prism-plugin/node_modules/anymatch
      chokidar  1.0.0-rc1 - 2.1.8
      Depends on vulnerable versions of anymatch
      Depends on vulnerable versions of glob-parent
      node_modules/hexo-prism-plugin/node_modules/chokidar
        hexo-fs  0.1.4 - 1.0.2
        Depends on vulnerable versions of chokidar
        node_modules/hexo-prism-plugin/node_modules/hexo-fs
          hexo-prism-plugin  *
          Depends on vulnerable versions of hexo-fs
          node_modules/hexo-prism-plugin

glob-parent  <5.1.2
Severity: high
glob-parent before 5.1.2 vulnerable to Regular Expression Denial of Service in enclosure regex - https://github.com/advisories/GHSA-ww39-953v-wcq6
No fix available
node_modules/glob-parent
  glob-base  *
  Depends on vulnerable versions of glob-parent
  node_modules/glob-base
    parse-glob  >=2.1.0
    Depends on vulnerable versions of glob-base
    node_modules/parse-glob

prismjs  <=1.24.1
Severity: high
Cross-Site Scripting in Prism - https://github.com/advisories/GHSA-wvhm-4hhf-97x9
prismjs Regular Expression Denial of Service vulnerability - https://github.com/advisories/GHSA-hqhp-5p83-hx96
Regular Expression Denial of Service (ReDoS) in Prism - https://github.com/advisories/GHSA-gj77-59wh-66hg
Denial of service in prismjs - https://github.com/advisories/GHSA-h4hr-7fg3-h35w
fix available via `npm audit fix`
node_modules/node-prismjs/node_modules/prismjs
  node-prismjs  >=0.1.1
  Depends on vulnerable versions of prismjs
  node_modules/node-prismjs

11 vulnerabilities (2 low, 1 moderate, 8 high)

To address issues that do not require attention, run:
  npm audit fix

Some issues need review, and may require choosing
a different dependency.
(xiaohui)  ✘ yuhui@yuhuideMacBook-Pro  ~/PycharmProjects/ngn_code/ngnlab-website-admin-master 
```
