const readmeStats = require('github-readme-stats');
await readmeStats({
username: '你的 GitHub 用户名',
show_icons: true,
title_color: 'blue',
text_color: 'green',
icon_color: 'white',
bg_color: 'black',
hide: ['issues', 'pulls', 'stars'],
token: '你的 GitHub 个人访问令牌'
});
