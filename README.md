# how_to_mermaid

## Live Editor

- [edit](https://mermaid.live/edit)

## Offical Site

- [mermaid](https://mermaid-js.github.io/)

## 方向

| 用词 | 含义 | Example |
| :-- | :-- | :-- |
| TB | 从上到下 | <pre><code class="mermaid">graph TB;<br>A-->B;<br></code></pre> |
| BT | 从下到上 | <pre><code class="mermaid">graph BT;<br>A-->B;<br></code></pre> |
| RL | 从右到左 | <pre><code class="mermaid">graph RL;<br>A-->B;<br></code></pre> |
| LR | 从左到右 | <pre><code class="mermaid">graph LR;<br>A-->B;<br></code></pre> |


## 节点形状

| 表述 | 说明 | Example |
| :-- | :-- | :-- |
| id[文字] | 矩形节点 | <pre><code class="mermaid">graph TB;<br>A[文字];<br></code></pre> |
| id(文字) | 圆角矩形节点 | <pre><code class="mermaid">graph TB;<br>A(文字);<br></code></pre> |
| id((文字)) | 圆形节点 | <pre><code class="mermaid">graph TB;<br>A((文字));<br></code></pre> |
| id>文字] | 右向旗帜状节点 | <pre><code class="mermaid">graph TB;<br>A>文字];<br></code></pre> |
| id{文字} | 菱形节点 | <pre><code class="mermaid">graph TB;<br>A{文字};<br></code></pre> |


## 节点连线

符号至少3个字符

| 表述 | 说明 | Example |
| :-- | :-- | :-- |
| --- | 单线 | <pre><code class="mermaid">graph LR;<br>A --- B;<br></code></pre> |
| ---text--- | 单线上加文字 | <pre><code class="mermaid">graph LR;<br>A ---text--- B;<br></code></pre> |
| === | 粗线 | <pre><code class="mermaid">graph LR;<br>A === B;<br></code></pre> |
| ===text=== | 粗线加文字 | <pre><code class="mermaid">graph LR;<br>A ===text=== B;<br></code></pre> |
| -.- | 虚线 | <pre><code class="mermaid">graph LR;<br>A -.- B;<br></code></pre> |
| -.text.- | 虚线加文字 | <pre><code class="mermaid">graph LR;<br>A -.text.- B;<br></code></pre> |
| .-> | 虚线加文字 | <pre><code class="mermaid">graph LR;<br>A .-> B;<br></code></pre> |
| --> | 虚线加文字 | <pre><code class="mermaid">graph LR;<br>A --> B;<br></code></pre> |

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
h2 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>




