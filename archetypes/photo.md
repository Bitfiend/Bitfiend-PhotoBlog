---
title: {{ replace .Name "-" " " }}
createdDay: {{ now.Format "Monday" }}
createdDate: {{ now.Format "January 2, 2006" }}
description: Descirption of the photo.
photographer: Linda Belcher
fileName: {{ .Name }}.ext
camera: 
tags: []
albums: []
draft: true
---
