<!--
 * @Description: 论坛组件
 * @Author: zyl
 -->
<template>
  <div  class="blog" id="blog" name="blog">
    <div class="breadcrumb">
      <el-breadcrumb separator-class="el-icon-arrow-right">
        <el-breadcrumb-item to="/">首页</el-breadcrumb-item>
        <el-breadcrumb-item>论坛</el-breadcrumb-item>
      </el-breadcrumb>
    </div>
<router-view>
  1
</router-view>

</div>
</template>
<!--
<template>
<div class="PostList">
<div class="loading" v-if="loading">
  Loading...
</div>

<div class="posts" v-else>
  <ul>

  <li v-for="post in posts">
      <router-link :to="{ name: 'user_info', params: { name: post.author.loginname }}" :title="post.author_id">
            <img :src="post.author.avatar_url" :title="post.author.loginname"/>
          </router-link>
          <span>
      {{ post.reply_count }}/{{ post.visit_count }}
          </span>
          <router-link :to="{ name: 'post_content', params: { id: post.id,name:post.author.loginname }}" :title="post.title">
            {{ post.title }}
          </router-link>
          <span class="last_reply">
            {{ post.last_reply_at | formatDate}}
          </span>
        </li>
          </ul>
        </div>
      </div>
    </template>
-->

