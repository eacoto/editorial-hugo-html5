+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
draft = true
tags = ['science','planets',]
[params]
    name = 'header'
    src = '/planets/*.jpg'
+++
