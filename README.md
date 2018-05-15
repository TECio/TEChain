# TEChain
TEChain是一个去中心化的专属于纺织行业生态的区块链，其核心是基于区块链去中心化、去信任中介的、不可篡改的特点，建立一个可信任的、更高效率的纺织产业的全流程的服务生态。
 “ test-cov ”： “ istanbul cover ./node_modules/mocha/bin/_mocha --t 500000000 --recursive -R spec test / ”，
    “ compile ”： “ babel --presets es2015-loose，stage-1 --plugins transform-runtime src / --out-dir lib / --source-maps ”，
    “ watch-compile ”： “ npm run compile  -  --watch ”，
    “ watch ”： “ npm run watch-compile ”，
    “ prepublish ”： “ npm run compile ”，
    “ eslint ”： “ eslint src / ”
  }，
  “贡献者”：[
    {
      “名称”： “ welefen ”，
      “ email ”： “ welefen@gmail.com ”
    }
  ]
  “ main ”： “ lib / index.js ”，
  “依赖关系”：{
    “ babel-generator ”： “ ^ 6.9.0 ”，
    “巴比伦”： “ ^ 6.8.0 ”，
    “ bluebird ”： “ ^ 3.4.0 ”，
    “ debug ”： “ ^ 2.2.0 ”，
    “ flkit ”： “ 3.xx ”，
    “ source-map-support ”： “ ^ 0.4.0 ”，
    “ stc-cache ”： “ 1.xx ”，
    “ stc-cluster ”： “ 1.xx ”，
    “ stc-dep-parser ”： “ 1.xx ”，
    “ stc-file ”： “ 1.xx ”，
    “ stc-helper ”： “ 1.xx ”，
    “ stc-log ”： “ 1.xx ”，
    “ stc-plugin ”： “ 1.xx ”，
    “ stc-plugin-invoke ”： “ 1.xx ”
  }，
  “ devDependencies ”：{
    “ ava ”： “ ^ 0.14.0 ”，
    “ babel-cli ”： “ 6.7.7 ”，
    “ babel-core ”： “ 6.xx ”，
    “ babel-eslint ”： “ 6.xx ”，
    “ babel-plugin-transform-runtime ”： “ 6.xx ”，
    “ babel-preset-es2015 ”： “ 6.xx ”，
    “ babel-preset-es2015-loose ”： “ 7.0.0 ”，
    “ babel-preset-stage-1 ”： “ 6.xx ”，
    “ eslint ”： “ 2.8.0 ”，
    “伊斯坦布尔”： “ 0.4.0 ”
  }，
  “关键字”：[]，
  “存储库”：{
    “ type ”： “ git ”，
    “ url ”： “ https://github.com/stcjs/stc ”
  }，
  “引擎”：{
    “ node ”： “ > = 4.0.0 ”
  }，
  “ readmeFilename ”： “ README.md ”，
  “错误”：{
    “ url ”： “ https://github.com/stcjs/stc/issues ”
  }
}
