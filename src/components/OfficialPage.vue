<template>
  <div class="app-container">
    <!-- Navigation -->
    <nav class="navbar">
      <div class="navbar-content">
        <div class="logo-section">
          <div class="logo">✨</div>
          <span class="app-title">Fingertip Dance</span>
        </div>
        <div class="nav-links">
          <a href="#features" class="nav-link">功能</a>
          <a href="#comparison" class="nav-link">对比</a>
          <a href="#download" class="nav-link">下载</a>
          <a href="#" class="nav-link-primary">开始使用</a>
        </div>
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
      <div class="hero-content">
        <h1 class="hero-title">指尖舞·为长文写作而生的创作编辑器</h1>
        <p class="hero-subtitle">
          一份代码，适配全平台。永远不会丢失的数据。精美的界面和友好的交互设计。
        </p>
        <div class="hero-buttons">
          <button class="btn btn-primary">立即开始</button>
          <button class="btn btn-secondary">了解更多</button>
        </div>
      </div>
      <div class="hero-visual">
        <div class="editor-preview">
          <div class="editor-top-bar">
            <div class="dot"></div>
            <div class="dot"></div>
            <div class="dot"></div>
          </div>
          <div class="editor-content">
            <div class="line"></div>
            <div class="line short"></div>
            <div class="line"></div>
            <div class="line short"></div>
          </div>
        </div>
      </div>
    </section>

    <!-- Key Features Section -->
    <section class="features" id="features">
      <h2 class="section-title">核心特点</h2>
      <div class="features-grid">
        <div class="feature-card">
          <div class="feature-icon">📝</div>
          <h3>Markdown 优先</h3>
          <p>专为 Markdown 编辑优化，比富文本更灵活、更强大</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">📂</div>
          <h3>文件夹管理</h3>
          <p>直观的文件夹结构，方便快捷的文件组织方式</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">🔒</div>
          <h3>数据永不丢失</h3>
          <p>多重备份机制，确保你的内容永远安全</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">⚡</div>
          <h3>极致性能</h3>
          <p>支持 2-10 万字以上的长文写作，流畅无阻</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">🎨</div>
          <h3>精美界面</h3>
          <p>遵循最佳交互设计体验，操作更加友好</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">🚀</div>
          <h3>跨平台支持</h3>
          <p>一份代码适配全部平台，各平台使用原生交互</p>
        </div>
      </div>
    </section>

    <!-- Comparison Section -->
    <section class="comparison" id="comparison">
      <h2 class="section-title">为什么选择 Fingertip Dance</h2>
      <div class="comparison-table-container">
        <table class="comparison-table">
          <thead>
            <tr>
              <th>特性</th>
              <th>Fingertip Dance</th>
              <th>Others </th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>编辑器类型</td>
              <td><span class="check">✓ Markdown 编辑器</span></td>
              <td><span class="cross">✗ 富文本编辑器</span></td>
            </tr>
            <tr>
              <td>目标用户</td>
              <td><span class="check">✓ 长文写作专业作家</span></td>
              <td><span class="cross">✗ 无明确分类</span></td>
            </tr>
            <tr>
              <td>文件管理</td>
              <td><span class="check">✓ 文件夹结构 + 快捷组织</span></td>
              <td><span class="cross">✗ 标签管理</span></td>
            </tr>
            <tr>
              <td>数据安全</td>
              <td><span class="check">✓ 永不丢失数据</span></td>
              <td><span class="cross">✗ 机制不确定</span></td>
            </tr>
            <tr>
              <td>交互设计</td>
              <td><span class="check">✓ 业界最佳实践</span></td>
              <td><span class="cross">✗ 设计不如 FD</span></td>
            </tr>
            <tr>
              <td>性能</td>
              <td><span class="check">✓ 超优秀（10万+字）</span></td>
              <td><span class="cross">✗ 普通</span></td>
            </tr>
            <tr>
              <td>跨平台</td>
              <td><span class="check">✓ 统一代码 + 原生交互</span></td>
              <td><span class="cross">✗ 多套代码</span></td>
            </tr>
            <tr>
              <td>开源许可</td>
              <td><span class="check">✓ 完全开源免费</span></td>
              <td><span class="cross">✗ 商业收费</span></td>
            </tr>
          </tbody>
        </table>
      </div>
    </section>

    <!-- Features Deep Dive -->
    <section class="features-deep-dive">
      <h2 class="section-title">功能全景</h2>
      
      <div class="feature-section">
        <h3 class="subsection-title">🎯 智能侧边栏</h3>
        <div class="feature-detail">
          <ul class="feature-list">
            <li>📌 <strong>全部文件</strong> - 一览无遗地查看所有内容</li>
            <li>❤️ <strong>收藏夹</strong> - 快速访问你最喜欢的文档</li>
            <li>📁 <strong>文件夹组</strong> - 自由组织和管理项目</li>
            <li>⏰ <strong>最近访问</strong> - 3-5 个最近编辑的文件夹</li>
            <li>🗑️ <strong>垃圾箱</strong> - 安全删除和快速恢复</li>
          </ul>
        </div>
      </div>

      <div class="feature-section">
        <h3 class="subsection-title">📊 文件管理中心</h3>
        <div class="feature-detail">
          <ul class="feature-list">
            <li>🔍 <strong>全文搜索</strong> - 快速查找任何内容</li>
            <li>✨ <strong>文档管理</strong> - 创建、删除、重命名、移动、导出</li>
            <li>💡 <strong>灵感采集</strong> - 便利贴式的想法记录和转化</li>
            <li>🗂️ <strong>文件夹管理</strong> - 自定义图标和颜色</li>
            <li>📤 <strong>导入导出</strong> - 灵活的文件流转</li>
          </ul>
        </div>
      </div>

      <div class="feature-section">
        <h3 class="subsection-title">✏️ 强大编辑器</h3>
        <div class="feature-detail">
          <ul class="feature-list">
            <li>🎮 <strong>快捷工具栏</strong> - 光标控制、编辑工具、快捷输入</li>
            <li>🤖 <strong>AI 助力</strong> - 续写、润色、翻译、实时对话</li>
            <li>↔️ <strong>光标控制</strong> - 前后移动、段落跳转、文档导航</li>
            <li>📈 <strong>文档状态</strong> - 实时字数统计、同步状态、保存提示</li>
            <li>⚙️ <strong>自定义编辑</strong> - 行高、字体、背景、主题全面定制</li>
          </ul>
        </div>
      </div>

      <div class="feature-section">
        <h3 class="subsection-title">☁️ 同步方案</h3>
        <div class="feature-detail">
          <ul class="feature-list">
            <li>🗄️ <strong>WebDAV 同步</strong> - 连接任意 WebDAV 服务，自由定制</li>
            <li>💾 <strong>本地同步</strong> - 使用本地数据库，无需配置</li>
            <li>🔄 <strong>智能同步策略</strong> - 仅同步结构、按需同步文档内容</li>
            <li>🔐 <strong>隐私保护</strong> - AI 对话记录不同步，确保隐私</li>
            <li>📱 <strong>多设备</strong> - 设备切换时轻松备份还原</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Call to Action -->
    <section class="cta-section">
      <div class="cta-content">
        <h2>准备好开始了吗？</h2>
        <p>加入数千位长文写作者，体验 Fingertip Dance 的强大功能</p>
        <div class="cta-buttons">
          <button class="btn btn-primary btn-large">现在下载</button>
          <button class="btn btn-secondary btn-large">查看文档</button>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="footer-content">
        <div class="footer-section">
          <h4>Fingertip Dance</h4>
          <p>为长文写作而生的 Markdown 编辑器</p>
        </div>
        <div class="footer-section">
          <h4>快速链接</h4>
          <ul>
            <li><a href="#">GitHub</a></li>
            <li><a href="#">文档</a></li>
            <li><a href="#">社区</a></li>
            <li><a href="#">支持</a></li>
          </ul>
        </div>
        <div class="footer-section">
          <h4>联系我们</h4>
          <ul>
            <li><a href="#">邮件</a></li>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">Discord</a></li>
          </ul>
        </div>
      </div>
      <div class="footer-bottom">
        <p>&copy; 2026 Fingertip Dance. All rights reserved. | Open Source & Free</p>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.app-container {
  width: 100%;
  overflow-x: hidden;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu',
    'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue', sans-serif;
  line-height: 1.6;
  color: #333;
}

/* Navbar */
.navbar {
  position: sticky;
  top: 0;
  background: rgba(255, 255, 255, 0.95);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid #e0e0e0;
  z-index: 100;
  padding: 1rem 0;
}

.navbar-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo-section {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  font-weight: 700;
  font-size: 1.5rem;
}

.logo {
  font-size: 2rem;
}

.app-title {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.nav-links {
  display: flex;
  gap: 2rem;
  align-items: center;
}

.nav-link {
  text-decoration: none;
  color: #666;
  font-weight: 500;
  transition: color 0.3s ease;
}

.nav-link:hover {
  color: #667eea;
}

.nav-link-primary {
  text-decoration: none;
  color: white;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  padding: 0.5rem 1.5rem;
  border-radius: 20px;
  font-weight: 600;
  transition: transform 0.3s ease;
}

.nav-link-primary:hover {
  transform: translateY(-2px);
}

/* Hero Section */
.hero {
  max-width: 1200px;
  margin: 0 auto;
  padding: 6rem 2rem;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: center;
}

.hero-content {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.hero-title {
  font-size: clamp(2rem, 5vw, 3.5rem);
  font-weight: 800;
  line-height: 1.2;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero-subtitle {
  font-size: 1.125rem;
  color: #666;
  line-height: 1.8;
}

.hero-buttons {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.btn {
  padding: 0.75rem 2rem;
  font-size: 1rem;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  font-weight: 600;
  transition: all 0.3s ease;
}

.btn-primary {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  box-shadow: 0 4px 15px rgba(102, 126, 234, 0.3);
}

.btn-primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(102, 126, 234, 0.4);
}

.btn-secondary {
  background: white;
  color: #667eea;
  border: 2px solid #667eea;
}

.btn-secondary:hover {
  background: #f5f5f5;
}

.btn-large {
  padding: 1rem 2.5rem;
  font-size: 1.125rem;
}

.editor-preview {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 10px 40px rgba(102, 126, 234, 0.2);
  min-height: 300px;
}

.editor-top-bar {
  display: flex;
  gap: 0.5rem;
  margin-bottom: 1.5rem;
}

.dot {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.4);
}

.editor-content {
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}

.line {
  height: 8px;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 4px;
}

.line.short {
  width: 70%;
}

/* Sections */
section {
  padding: 4rem 2rem;
  max-width: 1200px;
  margin: 0 auto;
}

.section-title {
  font-size: clamp(2rem, 4vw, 2.5rem);
  font-weight: 800;
  text-align: center;
  margin-bottom: 3rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

/* Features Grid */
.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
}

.feature-card {
  background: white;
  border-radius: 12px;
  padding: 2rem;
  text-align: center;
  border: 1px solid #e0e0e0;
  transition: all 0.3s ease;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

.feature-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.1);
  border-color: #667eea;
}

.feature-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.feature-card h3 {
  font-size: 1.25rem;
  margin-bottom: 0.75rem;
  color: #333;
}

.feature-card p {
  color: #666;
  font-size: 0.95rem;
}

/* Comparison Table */
.comparison {
  background: #f8f9ff;
}

.comparison-table-container {
  overflow-x: auto;
}

.comparison-table {
  width: 100%;
  border-collapse: collapse;
  background: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

.comparison-table thead {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
}

.comparison-table th,
.comparison-table td {
  padding: 1.25rem;
  text-align: left;
  border-bottom: 1px solid #e0e0e0;
}

.comparison-table tbody tr:last-child td {
  border-bottom: none;
}

.comparison-table tbody tr:hover {
  background: #f8f9ff;
}

.check {
  color: #10b981;
  font-weight: 600;
}

.cross {
  color: #ef4444;
  font-weight: 600;
}

/* Features Deep Dive */
.features-deep-dive {
  background: #f8f9ff;
}

.subsection-title {
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: #333;
}

.feature-section {
  margin-bottom: 3rem;
  background: white;
  padding: 2rem;
  border-radius: 12px;
  border-left: 4px solid #667eea;
}

.feature-list {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.feature-list li {
  font-size: 1rem;
  color: #666;
  line-height: 1.8;
}

.feature-list strong {
  color: #333;
}

/* CTA Section */
.cta-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  text-align: center;
  border-radius: 12px;
  padding: 4rem 2rem;
}

.cta-content h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.cta-content p {
  font-size: 1.125rem;
  margin-bottom: 2rem;
  opacity: 0.95;
}

.cta-buttons {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.cta-section .btn-primary {
  background: white;
  color: #667eea;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
}

.cta-section .btn-secondary {
  background: transparent;
  color: white;
  border-color: white;
}

.cta-section .btn-secondary:hover {
  background: rgba(255, 255, 255, 0.1);
}

/* Footer */
.footer {
  background: #1a1a2e;
  color: white;
  padding: 3rem 2rem 1rem;
  margin-top: 4rem;
}

.footer-content {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-bottom: 2rem;
}

.footer-section h4 {
  margin-bottom: 1rem;
  font-size: 1.125rem;
}

.footer-section p {
  color: #aaa;
  font-size: 0.95rem;
}

.footer-section ul {
  list-style: none;
}

.footer-section a {
  color: #aaa;
  text-decoration: none;
  transition: color 0.3s ease;
  display: inline-block;
  margin-bottom: 0.5rem;
}

.footer-section a:hover {
  color: #667eea;
}

.footer-bottom {
  text-align: center;
  padding-top: 2rem;
  border-top: 1px solid #333;
  color: #666;
}

/* Responsive */
@media (max-width: 768px) {
  .navbar-content {
    flex-direction: column;
    gap: 1rem;
  }

  .nav-links {
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
  }

  .hero {
    grid-template-columns: 1fr;
    padding: 3rem 1rem;
  }

  .hero-title {
    font-size: 2rem;
  }

  .hero-buttons {
    flex-direction: column;
  }

  .btn {
    width: 100%;
    text-align: center;
  }

  section {
    padding: 2rem 1rem;
  }

  .features-grid {
    grid-template-columns: 1fr;
  }

  .comparison-table {
    font-size: 0.9rem;
  }

  .comparison-table th,
  .comparison-table td {
    padding: 0.75rem;
  }

  .cta-content h2 {
    font-size: 1.75rem;
  }

  .footer-content {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 480px) {
  .hero-title {
    font-size: 1.5rem;
  }

  .section-title {
    font-size: 1.5rem;
  }

  .navbar-content {
    padding: 0 1rem;
  }

  .nav-links {
    gap: 0.5rem;
  }

  .nav-link {
    font-size: 0.9rem;
  }
}
</style>
