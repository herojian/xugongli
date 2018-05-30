---
layout: post
title: 判断pandas的两个DataFrame是否相同
description: pandas.DataFrame.equals
category: tech
---
# 官网说明
> DataFrame.equals(other)[source]¶
Determines if two NDFrame objects contain the same elements. NaNs in the same location are considered equal.

# 使用方法
results = df1.equals(df2)
results取值：True or False