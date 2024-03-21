本文件记录了手动对MediaWiki源代码进行的改动，以便于后续排查。
* 2023-05-22 ./includes/specialpage/QueryPage.php: 注释了public function reallyDoQuery调用MWDebug::detectDeprecatedOverride的部分，避免DEPRECATED报错的出现
* 2023-07-01 ./extensions/SemanticMediaWiki/src/Utils/TemplateEngine.php: public function compile中加入了对$value的is_null检查，避免DEPRECATED报错的出现
