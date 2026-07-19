<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>中药学与方剂学知识库 - 解表药</title>
    <style>
        @page {
            size: A4;
            margin: 20mm 16mm;
            background-color: #fafafa;
        }
        * { box-sizing: border-box; }
        body {
            margin: 0; padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            color: #2c3e50; background-color: #fafafa;
            line-height: 1.6; font-size: 10.5pt;
        }
        .header {
            margin-bottom: 25px; padding-bottom: 15px; border-bottom: 1px solid #eaeaea;
        }
        .header h1 { font-size: 20pt; font-weight: 500; color: #1a1a1a; margin: 0 0 8px 0; }
        .header p { font-size: 10pt; color: #8c8c8c; margin: 0; }
        
        /* 面包屑导航 */
        .breadcrumb { font-size: 9.5pt; color: #7f8c8d; margin-bottom: 20px; }
        .breadcrumb a { color: #3498db; text-decoration: none; }
        
        /* 章节/大类样式 */
        .section-title {
            font-size: 14pt; font-weight: 600; color: #1a1a1a;
            margin: 25px 0 15px 0; padding-left: 8px; border-left: 3px solid #2c3e50;
        }
        
        /* 子类区块 */
        .subsection {
            background: #ffffff; border: 1px solid #eef0f2; border-radius: 6px;
            margin-bottom: 20px; padding: 15px 18px;
        }
        .subsection-title {
            font-size: 12pt; font-weight: 600; color: #2c3e50; margin-top: 0; margin-bottom: 12px;
            padding-bottom: 6px; border-bottom: 1px dashed #f1f2f6;
        }
        
        /* 药物列表（Anki层级折叠） */
        details {
            background: #f8f9fa; border: 1px solid #f1f2f6; border-radius: 4px;
            margin: 8px 0; padding: 10px 12px;
        }
        details[open] { background: #ffffff; border-color: #bdc3c7; }
        summary { font-weight: 500; cursor: pointer; outline: none; color: #34495e; font-size: 11pt; }
        
        /* 药物详细卡片内容 */
        .drug-details {
            margin-top: 10px; padding-top: 10px; border-top: 1px solid #f1f2f6;
        }
        .meta-grid {
            display: flex; flex-wrap: wrap; gap: 15px; margin-bottom: 10px;
            font-size: 9.5pt; background: #fafafa; padding: 8px; border-radius: 4px;
        }
        .meta-item strong { color: #7f8c8d; }
        
        .content-block { margin-bottom: 8px; font-size: 10pt; }
        .content-block strong { color: #2c3e50; }
        
        /* 超链接设计 - 为未来方剂学预留 */
        .link-formula {
            color: #e67e22; text-decoration: none; background: #fdf5e6;
            padding: 1px 5px; border-radius: 3px; font-size: 9pt; font-weight: 500;
        }
        .link-formula:hover { background: #f39c12; color: #fff; }
    </style>
</head>
<body>

    <div class="header">
        <h1>中药学数字化知识库</h1>
        <p>多维关联系统 · 专为高效记诵与临床方剂串联设计</p>
    </div>

    <div class="breadcrumb">
        当前位置：<a href="#tcm-index">总知识库</a> ➔ <a href="#jiebiaoyao">解表药</a>
    </div>

    <div id="jiebiaoyao">
        <div class="section-title">第一章 解表药</div>
        <p style="color: #7f8c8d; font-size: 9.5pt; margin-top: -5px; margin-bottom: 15px;">
            凡以发散表邪、治疗表证为主的药物，称为解表药。多具辛味，主入肺、膀胱经。
        </p>

        <!-- 子选项：辛温解表 -->
        <div class="subsection" id="xinwen">
            <div class="subsection-title">一、辛温解表药（发散风寒药）</div>
            <p style="color: #95a5a6; font-size: 9pt; margin-top: -8px; margin-bottom: 10px;">适用于风寒表证（恶寒重、发热轻、无汗、脉浮紧等）。</p>
            
            <!-- 药物：麻黄 -->
            <details id="mahuang">
                <summary>🌿 麻黄 (Mahuang)</summary>
                <div class="drug-details">
                    <div class="meta-grid">
                        <div class="meta-item"><strong>药性：</strong>辛、微苦，温</div>
                        <div class="meta-item"><strong>归经：</strong>肺、膀胱经</div>
                        <div class="meta-item"><strong>功效：</strong>发汗解表、宣肺平喘、利水消肿</div>
                    </div>
                    <div class="content-block">
                        <strong>💡 考试与治疗要点：</strong>
                        主治外感风寒表实证（无汗项强）。为“发汗解表之要药”、“宣肺平喘之要药”。利水常用于风水水肿。
                    </div>
                    <div class="content-block">
                        <strong>🧪 预留方剂学串联：</strong>
                        <a href="#mahuang-tang" class="link-formula">【麻黄汤】 ↗</a> 
                        <a href="#ma-xing-shi-gan-tang" class="link-formula">【麻杏石甘汤】 ↗</a> 
                        <a href="#xiao-qing-long-tang" class="link-formula">【小青龙汤】 ↗</a>
                    </div>
                </div>
            </details>

            <!-- 药物：桂枝 -->
            <details id="guizhi">
                <summary>🌿 桂枝 (Guizhi)</summary>
                <div class="drug-details">
                    <div class="meta-grid">
                        <div class="meta-item"><strong>药性：</strong>辛、甘，温</div>
                        <div class="meta-item"><strong>归经：</strong>心、肺、膀胱经</div>
                        <div class="meta-item"><strong>功效：</strong>发汗解肌、温通经脉、助阳化气</div>
                    </div>
                    <div class="content-block">
                        <strong>💡 考试与治疗要点：</strong>
                        不论表实无汗（配麻黄）、表虚有汗（配白芍）均可使用。温通经脉常用于胸痹心痛、痛经、风湿痹痛。
                    </div>
                    <div class="content-block">
                        <strong>🧪 预留方剂学串联：</strong>
                        <a href="#guizhi-tang" class="link-formula">【桂枝汤】 ↗</a> 
                        <a href="#dang-gui-si-ni-tang" class="link-formula">【当归四逆汤】 ↗</a>
                    </div>
                </div>
            </details>
        </div>

        <!-- 子选项：辛凉解表 -->
        <div class="subsection" id="xinliang">
            <div class="subsection-title">二、辛凉解表药（发散风热药）</div>
            <p style="color: #95a5a6; font-size: 9pt; margin-top: -8px; margin-bottom: 10px;">适用于风热表证（发热重、恶寒轻、咽痛、脉浮数等）。</p>
            
            <!-- 药物：薄荷 -->
            <details id="bohe">
                <summary>🌿 薄荷 (Bohe)</summary>
                <div class="drug-details">
                    <div class="meta-grid">
                        <div class="meta-item"><strong>药性：</strong>辛，凉</div>
                        <div class="meta-item"><strong>归经：</strong>肺、肝经</div>
                        <div class="meta-item"><strong>功效：</strong>疏散风热、清利头目、利咽透疹、疏肝行气</div>
                    </div>
                    <div class="content-block">
                        <strong>💡 考试与治疗要点：</strong>
                        善治外感风热、头痛目赤、咽喉肿痛。注意：**后下**。疏肝行气常用于肝郁气滞证。
                    </div>
                    <div class="content-block">
                        <strong>🧪 预留方剂学串联：</strong>
                        <a href="#yin-qiao-san" class="link-formula">【银翘散】 ↗</a> 
                        <a href="#xiao-yao-san" class="link-formula">【逍遥散】 ↗</a>
                    </div>
                </div>
            </details>
        </div>
    </div>

</body>
</html>
