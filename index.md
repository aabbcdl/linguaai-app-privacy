# LinguaAI Privacy Policy

Last Updated: February 20, 2026  
Effective Date: February 20, 2026

<div style="margin: 16px 0; padding: 12px; border: 1px solid #d0d7de; border-radius: 8px; background: #f6f8fa;">
  <label for="langSelect"><strong>Language / 语言：</strong></label>
  <select id="langSelect" onchange="showLanguage(this.value)" style="margin-left:8px; padding:4px 8px;">
    <option value="en">English</option>
    <option value="zh">简体中文</option>
  </select>
</div>

> The English version is the authoritative version. Non-English versions are provided for convenience only.

<div class="lang-section" data-lang="en">

## 1. Introduction and Scope

This Privacy Policy explains how LinguaAI ("App") collects, uses, shares, stores, and deletes data.

This policy applies to processing through:
- The LinguaAI Android app
- Our backend API gateway (Cloudflare Worker)
- Integrated third-party SDKs and service providers listed in Section 6

## 2. Data We Process

We process only data needed for core features, security, abuse prevention, diagnostics, analytics, ads, and legal compliance.

### 2.1 Data You Create in App
- Translation history
- Vocabulary and learning records
- Generated content history
- App preferences and settings

### 2.2 Device and Technical Data
- App-generated pseudonymous device identifier (quota, anti-abuse, security)
- App/device technical metadata
- Network metadata at API edge (for example IP address)
- Security/rate-limit counters and operational metrics

### 2.3 Sensitive Permissions and Boundaries
Current Android permissions:
- `CAMERA`
- `RECORD_AUDIO`
- `INTERNET`

Boundaries:
- Camera/microphone permissions are requested only when you actively use related features (not at app launch).
- If you deny camera/microphone permission, related feature(s) will not work, but other core text-based features remain available.
- The App does not currently request location runtime permission.
- We do not use camera/audio permission for unrelated profiling or advertising.

### 2.4 Purchases
Google Play Billing processes payment/transaction data. We do not store full payment card details.

### 2.5 Ads, Analytics, Diagnostics
Depending on SDK behavior and settings:
- Ad serving/measurement/anti-fraud (AdMob)
- Product analytics (Firebase Analytics)
- Crash diagnostics (Firebase Crashlytics)

## 3. Purposes of Processing

We process data to:
- Provide translation and language-learning features
- Support network AI features via backend routing
- Enforce quota limits and anti-abuse controls
- Serve and measure ads
- Improve app quality and performance
- Detect crashes, security issues, and fraud
- Meet legal obligations

## 4. Backend Processing and Retention

When network features are used, requests are processed by our backend (Cloudflare Worker).

### 4.1 Backend Data Categories
- API request payloads needed to serve requested features
- Pseudonymous device ID headers
- Edge network metadata (for example IP)
- Security, anti-abuse, and rate-limit state

### 4.2 Backend Purposes
- Route requests to configured model providers
- Prevent abuse/fraud/replay and enforce limits
- Operate reward challenge/claim integrity flow
- Support operations, reliability, and incident response

### 4.3 Typical Retention
TTL-based operational retention, for example:
- Metrics: up to about 35 days
- Risk/abuse state: short-term TTL (configurable)
- Reward challenge state: short-lived (minutes)

If law requires longer retention, legal requirements prevail.

## 5. Server-Side Data Deletion Requests

Even without standalone LinguaAI account registration, you may request deletion of linkable server-side data.

How to request:
- Email: **cdlcdl9527@gmail.com**
- Subject: "Server Data Deletion Request"
- Include matching info (for example app-generated device ID, approximate time window, country/region, app version)

Process:
- We acknowledge and verify the request.
- We process valid requests within 30 calendar days (or faster if local law requires).
- We send completion confirmation by email.
- If data must be retained for law/security/fraud reasons, we restrict processing to those required purposes and explain why.

## 6. Third-Party Services and Sharing

We do not sell personal data for money.

Under Google Play policy, developers remain responsible for third-party SDK behavior inside the app.

Services used:
1. Google ML Kit - OCR/translation/speech processing  
   Policy: https://policies.google.com/privacy
2. Google AdMob - ad serving/measurement/anti-fraud  
   Policy: https://policies.google.com/privacy
3. Google Play Billing / Google Play Services - purchase and Play services  
   Policy: https://policies.google.com/privacy
4. Firebase Analytics - usage analytics  
   Policy: https://firebase.google.com/support/privacy
5. Firebase Crashlytics - crash diagnostics  
   Policy: https://firebase.google.com/support/privacy
6. Cloudflare - API gateway/edge security/traffic handling  
   Policy: https://www.cloudflare.com/privacypolicy/
7. AI providers configured by backend (for example Google Gemini API, OpenAI API)  
   Policies: https://policies.google.com/privacy, https://openai.com/policies/privacy-policy

We may disclose data when required by law, legal process, or to protect rights/safety/security.

## 7. Advertising and Sensitive Category Restrictions

- We do not intentionally use sensitive categories (race, religion, sexual orientation, health status, financial hardship, etc.) for personalized advertising.
- We do not intentionally use your local translation content, vocabulary records, or generated AI content as direct inputs for personalized ad targeting.
- You can manage ad personalization in Google Ads/device settings.

## 8. Sale/Share Statement

- Under Google Play policy, "sale" generally refers to exchange/transfer of personal and sensitive data for monetary consideration.
- Where applicable law defines sale/share more broadly (for example other valuable consideration), we apply applicable legal requirements.

## 9. User Rights and Response Time

Depending on your jurisdiction, you may have rights such as access, correction, deletion, portability, objection/restriction, and complaint.

How to exercise rights:
- Email: **cdlcdl9527@gmail.com**
- In-app: Settings -> Send Feedback

Response time:
- We respond to valid requests within 30 calendar days, unless a shorter legal deadline applies.

## 10. No Standalone LinguaAI Account

The App currently does not provide standalone LinguaAI account registration/login.

Therefore, account-deletion workflows for in-app accounts do not apply. Server-side deletion requests are handled via Section 5.

## 11. Children

The App is not directed to children. We do not knowingly collect personal data from children under 13, or under a higher local legal minimum age.

If such data is identified, we will take steps to delete it.

## 12. Security

We use reasonable safeguards, including:
- HTTPS/TLS for network transmission
- Access controls and least-privilege operations
- Anti-abuse monitoring and security controls
- Incident response procedures

No method is 100% secure, but safeguards are continuously improved.

## 13. Business Transfer

If merger/acquisition/reorganization/bankruptcy/asset transfer occurs:
- We provide notice before material transfer of personal data (typically at least 30 days where feasible/required).
- The receiving party must protect data with terms no less protective than this policy.
- Where legally available, you may request deletion before transfer takes effect.

## 14. Cross-Border Processing

Data may be processed outside your country through global providers. We apply safeguards required by applicable law.

## 15. Southeast Asia Compliance

For users in Southeast Asia (including Singapore, Indonesia, Thailand, Malaysia, Vietnam), we process data in accordance with applicable local data protection requirements.

## 16. Tracking Technologies

The app and SDKs may use identifiers and similar technologies (for example Android advertising identifiers and SDK telemetry) for ads, analytics, diagnostics, security, and anti-fraud.

You can manage ad personalization and reset advertising identifiers in Google Ads settings.

## 17. In-App Prominent Disclosure and Consent

Where required by Google Play policy, we provide in-app prominent disclosure and require affirmative user action before processing personal/sensitive data outside reasonable user expectation.

## 18. Policy Accessibility and Language

- This policy is available in-app (Settings -> Privacy Policy) and on a public HTTPS URL.
- No login is required to view the web policy.
- If multiple language versions conflict, the English version controls.

## 19. Changes to This Policy

We may update this policy when features, providers, legal requirements, or processing practices change.

For material changes, we provide prominent notice where required.

## 20. Contact

- Email: **cdlcdl9527@gmail.com**
- In-app feedback: Settings -> Send Feedback

</div>

<div class="lang-section" data-lang="zh" style="display:none;">

## 1. 适用范围

本隐私政策说明 LinguaAI（“本应用”）如何收集、使用、共享、存储和删除数据。

本政策适用于以下处理场景：
- LinguaAI Android 应用
- 我们的后端 API 网关（Cloudflare Worker）
- 第 6 节列出的第三方 SDK 与服务商

## 2. 我们处理的数据

我们遵循最小必要原则，仅处理实现核心功能、安全风控、反滥用、诊断分析、广告与法律合规所需的数据。

### 2.1 你在应用内创建的数据
- 翻译历史
- 词汇与学习记录
- AI 生成内容历史
- 应用偏好设置

### 2.2 设备与技术数据
- 应用生成的假名化设备标识（用于配额、反滥用、安全）
- 应用/设备技术元数据
- API 边缘网络元数据（如 IP）
- 安全、限流与运维指标

### 2.3 敏感权限与边界
当前 Android 权限：
- `CAMERA`
- `RECORD_AUDIO`
- `INTERNET`

处理边界：
- 相机/麦克风权限仅在你主动使用对应功能时请求，不会在启动时强制请求。
- 若拒绝相机/麦克风权限，仅对应功能不可用，其他文本类核心功能仍可使用。
- 当前实现不申请定位运行时权限。
- 我们不会将相机/音频权限用于无关画像或广告用途。

### 2.4 支付与订阅
应用内购买由 Google Play Billing 处理，我们不存储完整银行卡信息。

### 2.5 广告、分析与诊断
根据 SDK 与设置，可能处理：
- AdMob 广告投放/测量/反作弊
- Firebase Analytics 产品分析
- Firebase Crashlytics 崩溃诊断

## 3. 数据用途

- 提供翻译与语言学习功能
- 通过后端路由支持联网 AI 功能
- 执行配额与反滥用控制
- 展示与测量广告
- 提升应用质量与性能
- 识别崩溃、安全问题与欺诈行为
- 履行法律义务

## 4. 后端处理与保留

使用联网功能时，请求会经过我们的 Cloudflare Worker 后端。

### 4.1 后端处理数据类别
- 提供服务所需的 API 请求内容
- 假名化设备标识头
- 边缘网络元数据（如 IP）
- 安全、反滥用、限流状态

### 4.2 后端处理目的
- 路由请求到已配置模型服务商
- 防重放、防滥用、防欺诈与限流
- 维护奖励 challenge/claim 完整性
- 支持运维监控与事件处置

### 4.3 典型保留周期
采用 TTL 限时保留，例如：
- 指标数据约 35 天
- 风控/反滥用状态短周期（可配置）
- 奖励 challenge 状态为分钟级短周期

如法律要求更长保留，按法律要求执行。

## 5. 服务器侧数据删除请求

即使本应用没有独立 LinguaAI 账号系统，你仍可请求删除可关联的服务器侧数据。

申请方式：
- 邮箱：**cdlcdl9527@gmail.com**
- 主题：`Server Data Deletion Request`
- 请提供匹配信息（如应用生成设备标识、时间范围、地区、应用版本）

处理流程：
- 我们会确认并核验请求。
- 对有效请求，我们会在 30 个自然日内完成处理（如地方法律要求更短，以其为准）。
- 处理完成后通过邮件确认。
- 若部分数据因法律/安全/反欺诈义务必须保留，我们将仅限于该目的处理并告知原因。

## 6. 第三方服务与共享

我们不会以金钱对价出售个人数据。

根据 Google Play 政策，开发者对集成 SDK 的数据行为承担合规责任。

使用的第三方服务：
1. Google ML Kit（OCR/翻译/语音相关）  
   https://policies.google.com/privacy
2. Google AdMob（广告投放/测量/反作弊）  
   https://policies.google.com/privacy
3. Google Play Billing / Google Play Services（支付与 Play 服务）  
   https://policies.google.com/privacy
4. Firebase Analytics（使用分析）  
   https://firebase.google.com/support/privacy
5. Firebase Crashlytics（崩溃诊断）  
   https://firebase.google.com/support/privacy
6. Cloudflare（API 网关与边缘安全）  
   https://www.cloudflare.com/privacypolicy/
7. 后端配置的 AI 服务商（如 Google Gemini、OpenAI）  
   https://policies.google.com/privacy  
   https://openai.com/policies/privacy-policy

在法律要求、司法程序或保护权利/安全需要时，我们可能依法披露必要数据。

## 7. 广告敏感类别限制

- 不会故意基于敏感类别（种族、宗教、性取向、健康、财务困境等）进行个性化广告。
- 不会故意将你的本地翻译内容、词汇记录、AI 生成内容直接用于个性化广告定向。
- 你可在设备 Google Ads 设置中管理个性化广告。

## 8. 出售/共享声明

- 在 Google Play 口径下，“出售”通常指以金钱对价交换/传输个人与敏感数据。
- 若适用法律对 sale/share 口径更广（如“其他有价值对价”），我们按当地法律执行并保障你的法定权利。

## 9. 用户权利与响应时限

你在适用法下可能享有访问、更正、删除、可携带、限制/反对处理、投诉等权利。

行权方式：
- 邮箱：**cdlcdl9527@gmail.com**
- 应用内：Settings -> Send Feedback

响应时限：
- 对有效请求通常在 30 个自然日内响应；如地方法律要求更短，以其为准。

## 10. 无独立 LinguaAI 账号

当前应用不提供 LinguaAI 独立注册/登录。

因此不适用“应用内账号删除流程”；服务器侧可关联数据删除请按第 5 节申请。

## 11. 儿童保护

本应用不面向儿童。我们不会明知收集 13 岁以下或地方法律要求更高最低年龄用户的个人数据；如发现，将尽快删除。

## 12. 安全措施

我们采用合理技术与管理措施，包括：
- HTTPS/TLS 传输加密
- 最小权限与访问控制
- 反滥用与安全监控
- 安全事件响应流程

## 13. 业务转让

若发生并购、重组、破产或资产转让：
- 在可行/法律要求下，通常至少提前 30 天通知。
- 受让方须履行不低于本政策的保护义务。
- 在法律允许范围内，你可在转让生效前申请删除数据。

## 14. 跨境处理

数据可能通过全球服务商在你所在国家/地区之外处理。我们将按适用法律采取必要保障措施。

## 15. 东南亚地区合规

针对新加坡、印尼、泰国、马来西亚、越南用户，我们按当地数据保护法律要求处理数据。

## 16. 跟踪技术

应用及 SDK 可能使用标识符与类似技术（如广告标识符、SDK 遥测机制）用于广告、分析、诊断、安全与反作弊。

你可在设备 Google Ads 设置中管理个性化广告与重置广告标识符。

## 17. 应用内显著披露与同意

对于超出合理预期的数据处理，按 Google Play 要求提供应用内显著披露，并在处理前取得用户明确主动同意。

## 18. 可访问性与语言

- 本政策可在应用内（Settings -> Privacy Policy）访问，并发布于公开 HTTPS 页面。
- 访问网页版本无需登录。
- 多语言版本存在差异时，以英文版为准。

## 19. 政策更新

当功能、服务商、法律要求或处理方式变化时，本政策会更新；重大变更将按要求进行显著通知。

## 20. 联系方式

- 邮箱：**cdlcdl9527@gmail.com**
- 应用内反馈：Settings -> Send Feedback

</div>

<script>
(function () {
  const select = document.getElementById('langSelect');
  const sections = document.querySelectorAll('.lang-section');

  function applyLang(lang) {
    sections.forEach((section) => {
      section.style.display = section.getAttribute('data-lang') === lang ? 'block' : 'none';
    });
    select.value = lang;
    try { localStorage.setItem('linguaai_policy_lang', lang); } catch (e) {}
  }

  window.showLanguage = function (lang) {
    applyLang(lang);
  };

  let initial = 'en';
  try {
    const saved = localStorage.getItem('linguaai_policy_lang');
    if (saved === 'en' || saved === 'zh') initial = saved;
    else if ((navigator.language || '').toLowerCase().startsWith('zh')) initial = 'zh';
  } catch (e) {
    if ((navigator.language || '').toLowerCase().startsWith('zh')) initial = 'zh';
  }

  applyLang(initial);
})();
</script>

