# 脱离上下文的 API

如果你用过想在 `setup` 外使用 `useDialog`、`useMessage`、`useNotification`、`useLoadingBar`，你可以通过 `createDiscreateApi` 来构建对应的 API。

<n-alert title="注意" type="warning">
  脱离上下文的 API 不会受 <n-text code>n-xxx-provider</n-text> 的影响，并且和应用上下文中对应组件会使用不同的 DOM 容器。如果需要的话，你需要手动同步这些信息。并且最好不要混用两类 API。
</n-alert>

## 演示

```demo
basic.vue
```

## API
