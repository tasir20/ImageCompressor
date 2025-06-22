<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- SEO Meta Tags -->
    <title>Free Image Compressor Online - Shrink JPG/PNG Size Without Losing Quality</title>
    <meta name="description" content="Compress JPG, PNG, WebP images online for free! Reduce file size by up to 90% without quality loss. Optimize photos for websites, social media & email. Fast, secure & batch-friendly.">
    <meta name="keywords" content="image compressor, compress image, jpg compressor, png optimizer, shrink image, photo compressor, reduce image size, image optimizer, compress photos, webp compressor, compress jpeg without losing quality online, bulk image compressor for ecommerce websites, reduce png file size with transparency, free high-resolution photo compressor tool, lossless webp compression online, shrink image size for email attachments, professional jpg optimizer for photographers, fast batch image compressor tool, compress images for website speed optimization, mobile-friendly image size reducer tool, best image compressor, free online image compressor, compress images for web, high-quality photo compressor, bulk image compression tool">

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

    <style>
        /* --- 1. General & Theming --- */
        :root {
            --primary-color: #6a5af9;
            --primary-hover: #5041d8;
            --secondary-color: #1e293b;
            --dark-bg-start: #1e293b;
            --dark-bg-end: #0f172a;
            --light-bg: #f1f5f9;
            --border-color: #cbd5e1;
            --text-light: #f8fafc;
            --text-dark: #334155;
            --text-muted: #64748b;
            --success-color: #10b981;
            --shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-image: linear-gradient(135deg, var(--dark-bg-start) 0%, var(--dark-bg-end) 100%);
            color: var(--text-dark);
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            padding: 20px 0;
        }

        /* --- 2. Ad & Page Layout --- */
        .page-container {
            display: flex;
            flex-direction: column;
            width: 100%;
            max-width: 1600px;
            align-items: center;
        }

        .ad-banner {
            background-color: rgba(30, 41, 59, 0.5);
            display: flex;
            justify-content: center;
            align-items: center;
            font-weight: 500;
            color: var(--text-muted);
            border: 1px dashed #475569;
            text-align: center;
            border-radius: 8px;
        }

        .ad-top-bottom {
            width: 95%;
            height: 90px;
            margin-bottom: 25px;
        }
        
        .ad-bottom {
             margin-top: 25px;
        }

        .main-content-wrapper {
            display: flex;
            width: 100%;
            justify-content: center;
            gap: 25px;
        }

        .ad-side {
            width: 160px;
            flex-shrink: 0;
        }

        /* --- 3. Main Tool Container & Thinner RGB Animation --- */
        .app-container {
            flex-grow: 1;
            max-width: 1000px;
            background-color: var(--text-light);
            border-radius: 16px;
            box-shadow: var(--shadow);
            padding: 30px 35px;
            position: relative;
            overflow: hidden;
        }
        
        @keyframes rgb-animation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .app-container::before {
            content: '';
            position: absolute;
            top: 0; right: 0; bottom: 0; left: 0;
            z-index: 0;
            background: linear-gradient(120deg, #ff0000, #ff7300, #fffb00, #48ff00, #00ffd5, #002bff, #7a00ff, #ff00c8, #ff0000);
            background-size: 300% 300%;
            animation: rgb-animation 10s ease infinite;
            filter: blur(4px); /* Smaller blur for thinner line */
            transform: scale(1.015); /* Slightly smaller scale */
        }
        
        .app-content {
            position: relative;
            z-index: 1;
            background: var(--text-light);
        }

        /* --- 4. Shared Control Styles --- */
        .control-group input, .control-group select {
            width: 100%;
            padding: 10px;
            border-radius: 6px;
            border: 1px solid var(--border-color);
            font-family: 'Inter', sans-serif;
            font-weight: 500;
            background-color: #fff;
            transition: all 0.2s ease;
        }

        .control-group input:focus, .control-group select:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 3px rgba(106, 90, 249, 0.2);
        }
        
        .control-group input:disabled, .control-group select:disabled {
            background-color: #e9ecef;
            cursor: not-allowed;
            opacity: 0.7;
        }

        /* --- 5. Updated Controls Area --- */
        .controls-area {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-bottom: 25px;
        }

        /* --- All other styles from the previous version remain largely the same --- */
        /* They are included here for completeness */
        .tool-header { text-align: center; margin-bottom: 30px; border-bottom: 1px solid var(--border-color); padding-bottom: 25px; }
        .tool-header h1 { font-weight: 700; color: var(--secondary-color); font-size: 2.2rem; }
        .tool-header p { font-size: 1.05rem; color: var(--text-muted); margin-top: 8px; max-width: 700px; margin-left: auto; margin-right: auto; }
        .upload-area { border: 3px dashed var(--border-color); border-radius: 12px; padding: 50px; text-align: center; cursor: pointer; transition: all 0.3s ease; background-color: #f8fafc; animation: pulse-animation 2s infinite; }
        @keyframes pulse-animation { 0% { transform: scale(1); } 50% { transform: scale(1.02); } 100% { transform: scale(1); } }
        .upload-area.drag-over { border-color: var(--primary-color); background-color: #f0eeff; animation: none; }
        .upload-icon svg { width: 60px; height: 60px; color: var(--primary-color); margin-bottom: 15px; transition: transform 0.3s ease; }
        .upload-area:hover .upload-icon svg { transform: scale(1.1); }
        .upload-text { font-size: 1.2rem; font-weight: 500; }
        .upload-text span { color: var(--primary-color); font-weight: 600; }
        #file-input { display: none; }
        .processing-section { display: none; }
        .controls-and-actions { background-color: #f8fafc; border: 1px solid var(--border-color); border-radius: 12px; padding: 25px; margin-bottom: 25px; }
        .control-group { display: flex; flex-direction: column; }
        .control-group label { font-weight: 600; margin-bottom: 10px; font-size: 0.95rem; color: var(--text-dark); }
        .control-group input[type="range"] { -webkit-appearance: none; appearance: none; width: 100%; height: 8px; background: var(--border-color); border-radius: 5px; outline: none; transition: opacity .2s; padding: 0; }
        .control-group input[type="range"]::-webkit-slider-thumb { -webkit-appearance: none; appearance: none; width: 20px; height: 20px; background: var(--primary-color); cursor: pointer; border-radius: 50%; border: 3px solid var(--text-light); box-shadow: 0 0 5px rgba(0,0,0,0.2); }
        .dimension-inputs { display: flex; gap: 10px; align-items: center; }
        .action-buttons { display: flex; justify-content: center; align-items: center; gap: 15px; flex-wrap: wrap; border-top: 1px solid var(--border-color); padding-top: 25px; }
        .btn { padding: 12px 28px; font-family: 'Inter', sans-serif; font-size: 1rem; font-weight: 600; border-radius: 8px; border: none; cursor: pointer; text-decoration: none; display: inline-flex; align-items: center; justify-content: center; transition: all 0.3s ease; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        .btn svg { width: 18px; height: 18px; margin-right: 8px; }
        #compress-btn { background: linear-gradient(45deg, var(--primary-color), var(--primary-hover)); color: var(--text-light); font-size: 1.1rem; padding: 14px 35px; }
        #compress-btn:hover { transform: translateY(-2px); box-shadow: 0 4px 10px rgba(106, 90, 249, 0.4); }
        #download-btn { background-color: var(--success-color); color: var(--text-light); }
        #download-btn:hover { background-color: #059669; }
        #reset-btn { background-color: var(--text-muted); color: var(--text-light); }
        #reset-btn:hover { background-color: #475569; }
        .preview-area { display: grid; grid-template-columns: 1fr 1fr; gap: 25px; }
        .preview-box { border: 1px solid var(--border-color); border-radius: 12px; padding: 20px; text-align: center; background: #fff; }
        .preview-box h3 { font-weight: 600; margin-bottom: 15px; color: var(--secondary-color); }
        .image-placeholder { width: 100%; min-height: 200px; display: flex; flex-direction: column; justify-content: center; align-items: center; border-radius: 6px; background-color: #f8fafc; color: var(--text-muted); }
        .image-placeholder svg { width: 48px; height: 48px; margin-bottom: 10px; }
        .preview-box img { max-width: 100%; height: auto; border-radius: 6px; margin-bottom: 15px; min-height: 200px; object-fit: contain; background-image: linear-gradient(45deg, #e2e8f0 25%, transparent 25%), linear-gradient(-45deg, #e2e8f0 25%, transparent 25%), linear-gradient(45deg, transparent 75%, #e2e8f0 75%), linear-gradient(-45deg, transparent 75%, #e2e8f0 75%); background-size: 20px 20px; background-position: 0 0, 0 10px, 10px -10px, -10px 0px; }
        .file-info { font-size: 0.95rem; font-weight: 500; background-color: var(--light-bg); padding: 10px; border-radius: 6px; }
        .file-info span { font-weight: 700; color: var(--primary-color); }
        #compressed-size.highlight { color: var(--success-color); font-weight: 700; }
        @media (max-width: 1200px) { .ad-side { display: none; } }
        @media (max-width: 768px) { body { padding: 0; } .page-container { padding: 10px; } .ad-top-bottom { width: 100%; } .app-container { padding: 20px 15px; } .tool-header h1 { font-size: 1.8rem; } .tool-header p { font-size: 0.9rem; } .controls-area { grid-template-columns: 1fr; } .preview-area { grid-template-columns: 1fr; } .action-buttons { flex-direction: column; } .btn { width: 100%; } }
    </style>
</head>
<body>

    <div class="page-container">
        <div class="ad-banner ad-top-bottom">Top Ad: compress images for website speed optimization</div>
        <div class="main-content-wrapper">
            <div class="ad-banner ad-side">Left Ad: professional jpg optimizer</div>
            <main class="app-container">
                <div class="app-content">
                    <header class="tool-header">
                        <h1>Ultimate Image Compressor</h1>
                        <p>Shrink JPG, PNG, & WebP files with our free online image compressor. Reduce file size by up to 90% using our powerful quality and target size controls. Perfect for web, email, and social media.</p>
                    </header>

                    <div class="upload-area" id="upload-area">
                        <input type="file" id="file-input" accept="image/jpeg,image/png,image/webp">
                        <div class="upload-icon"><svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path d="M19.35 10.04C18.67 6.59 15.64 4 12 4 9.11 4 6.6 5.64 5.35 8.04 2.34 8.36 0 10.91 0 14c0 3.31 2.69 6 6 6h13c2.76 0 5-2.24 5-5 0-2.64-2.05-4.78-4.65-4.96zM14 13v4h-4v-4H7l5-5 5 5h-3z"/></svg></div>
                        <p class="upload-text">Drag & drop an image or <span>click to browse</span></p>
                    </div>

                    <div class="processing-section" id="processing-section">
                        <div class="preview-area">
                            <div class="preview-box">
                                <h3>Original</h3>
                                <img id="original-preview" src="" alt="Original user-uploaded image">
                                <p class="file-info">Size: <span id="original-size">0 KB</span></p>
                            </div>
                            <div class="preview-box">
                                <h3>Compressed</h3>
                                <div id="compressed-placeholder" class="image-placeholder">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path d="M9.4 16.6 4.8 12l4.6-4.6L8 6l-6 6 6 6 1.4-1.4zm5.2 0 4.6-4.6-4.6-4.6L16 6l6 6-6 6-1.4-1.4z"/></svg>
                                    <p>Adjust settings & press Compress</p>
                                </div>
                                <img id="compressed-preview" src="" alt="Compressed image result" style="display:none;">
                                <p class="file-info" id="compressed-info" style="display:none;">Size: <span id="compressed-size">0 KB</span></p>
                            </div>
                        </div>

                        <div class="controls-and-actions">
                            <div class="controls-area">
                                <div class="control-group">
                                    <label>Output Format</label>
                                    <select id="format-select">
                                        <option value="auto" selected>Auto</option>
                                        <option value="jpeg">JPG</option>
                                        <option value="png">PNG</option>
                                        <option value="webp">WEBP</option>
                                    </select>
                                </div>
                                <div class="control-group">
                                    <label for="quality-slider">Quality (<span id="quality-value">0.80</span>)</label>
                                    <input type="range" id="quality-slider" min="0.1" max="1" step="0.05" value="0.8">
                                </div>
                                <div class="control-group">
                                    <label for="max-size-input">Target Size (KB)</label>
                                    <input type="number" id="max-size-input" placeholder="Optional, e.g., 100">
                                </div>
                                <div class="control-group">
                                    <label>Resize Dimensions (px)</label>
                                    <div class="dimension-inputs">
                                        <input type="number" id="width-input" placeholder="Width">
                                        <input type="number" id="height-input" placeholder="Height">
                                    </div>
                                    <div style="margin-top:10px;">
                                        <input type="checkbox" id="aspect-ratio-lock" checked><label for="aspect-ratio-lock" style="font-weight:400; font-size:0.9rem; cursor:pointer;"> Lock Aspect Ratio</label>
                                    </div>
                                </div>
                            </div>
                            <div class="action-buttons">
                                <button id="compress-btn" class="btn">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path d="m15 9-2.5-2.5L10 9l-1.5-1.5L6 10l2.5 2.5L6 15l1.5 1.5L10 14l2.5 2.5L15 14l-2.5-2.5L15 9zm-9 3-2.5-2.5L6 7l1.5 1.5L5 11l2.5 2.5L5 16l-1.5-1.5L6 12zm12 0-2.5-2.5L18 7l1.5 1.5L17 11l2.5 2.5L17 16l-1.5-1.5L18 12z"/></svg>
                                    Compress
                                </button>
                                <a href="#" id="download-btn" class="btn" download style="display: none;">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path d="M19 9h-4V3H9v6H5l7 7 7-7zM5 18v2h14v-2H5z"/></svg>
                                    Download
                                </a>
                                <button id="reset-btn" class="btn">
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path d="M17.65 6.35C16.2 4.9 14.21 4 12 4c-4.42 0-7.99 3.58-7.99 8s3.57 8 7.99 8c3.73 0 6.84-2.55 7.73-6h-2.08c-.82 2.33-3.04 4-5.65 4-3.31 0-6-2.69-6-6s2.69-6 6-6c1.66 0 3.14.69 4.22 1.78L13 11h7V4l-2.35 2.35z"/></svg>
                                    Start Over
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </main>
            <div class="ad-banner ad-side">Right Ad: mobile-friendly image reducer</div>
        </div>
        <div class="ad-banner ad-top-bottom ad-bottom">Bottom Ad: shrink image size for email</div>
    </div>

<script>
document.addEventListener('DOMContentLoaded', () => {
    // --- DOM Element References ---
    const uploadArea = document.getElementById('upload-area');
    const fileInput = document.getElementById('file-input');
    const processingSection = document.getElementById('processing-section');
    const qualitySlider = document.getElementById('quality-slider');
    const qualityValue = document.getElementById('quality-value');
    const widthInput = document.getElementById('width-input');
    const heightInput = document.getElementById('height-input');
    const aspectRatioLock = document.getElementById('aspect-ratio-lock');
    const maxSizeInput = document.getElementById('max-size-input');
    const formatSelect = document.getElementById('format-select');
    const originalPreview = document.getElementById('original-preview');
    const compressedPreview = document.getElementById('compressed-preview');
    const compressedPlaceholder = document.getElementById('compressed-placeholder');
    const originalSize = document.getElementById('original-size');
    const compressedSize = document.getElementById('compressed-size');
    const compressedInfo = document.getElementById('compressed-info');
    const compressBtn = document.getElementById('compress-btn');
    const downloadBtn = document.getElementById('download-btn');
    const resetBtn = document.getElementById('reset-btn');

    let originalImageFile = null;
    let originalImageWidth = 0;
    let originalImageHeight = 0;

    // --- Utility Functions ---
    const formatBytes = (bytes, decimals = 2) => {
        if (!+bytes) return '0 Bytes';
        const k = 1024;
        const dm = decimals < 0 ? 0 : decimals;
        const sizes = ['Bytes', 'KB', 'MB', 'GB', 'TB'];
        const i = Math.floor(Math.log(bytes) / Math.log(k));
        return `${parseFloat((bytes / Math.pow(k, i)).toFixed(dm))} ${sizes[i]}`;
    };

    const dataURLtoBlob = (dataurl) => {
        const arr = dataurl.split(','), mime = arr[0].match(/:(.*?);/)[1];
        const bstr = atob(arr[1]);
        let n = bstr.length;
        const u8arr = new Uint8Array(n);
        while (n--) u8arr[n] = bstr.charCodeAt(n);
        return new Blob([u8arr], { type: mime });
    };

    // --- Core Compression Logic ---
    const drawImageToCanvas = (img, width, height, mimeType, quality) => {
        const canvas = document.createElement('canvas');
        canvas.width = width;
        canvas.height = height;
        const ctx = canvas.getContext('2d');
        ctx.drawImage(img, 0, 0, width, height);
        return canvas.toDataURL(mimeType, quality);
    };

    const compressImage = async () => {
        if (!originalImageFile) return;

        compressBtn.disabled = true;
        compressBtn.textContent = 'Compressing...';

        const maxWidth = parseInt(widthInput.value);
        const maxHeight = parseInt(heightInput.value);
        const targetSizeKB = parseInt(maxSizeInput.value);
        const outputFormat = formatSelect.value;
        
        let mimeType = 'image/jpeg';
        if (outputFormat === 'auto') {
            mimeType = originalImageFile.type === 'image/png' ? 'image/png' : 'image/jpeg';
        } else {
            mimeType = `image/${outputFormat}`;
        }
        // PNG doesn't support quality adjustments in browsers
        if (mimeType === 'image/png') qualitySlider.value = 1.0;
        
        const reader = new FileReader();
        reader.readAsDataURL(originalImageFile);
        reader.onload = async (event) => {
            const img = new Image();
            img.src = event.target.result;
            img.onload = async () => {
                let compressedDataUrl;
                let finalBlob;

                if (!isNaN(targetSizeKB) && targetSizeKB > 0 && mimeType !== 'image/png') {
                    // Smart compression to target size
                    const targetSizeBytes = targetSizeKB * 1024;
                    let currentQuality = 0.95;
                    let bestUrl = '';
                    
                    // Binary search for quality would be faster, but this is simpler and effective
                    for (let q = currentQuality; q >= 0.1; q -= 0.05) {
                        const dataUrl = drawImageToCanvas(img, maxWidth, maxHeight, mimeType, q);
                        const blob = dataURLtoBlob(dataUrl);
                        if (blob.size <= targetSizeBytes) {
                           bestUrl = dataUrl;
                           break; // Found a good enough quality
                        }
                        if (q < currentQuality) bestUrl = dataUrl; // Keep the last one if all are too big
                    }
                    compressedDataUrl = bestUrl || drawImageToCanvas(img, maxWidth, maxHeight, mimeType, 0.1);

                } else {
                    // Standard compression with slider
                    const quality = parseFloat(qualitySlider.value);
                    compressedDataUrl = drawImageToCanvas(img, maxWidth, maxHeight, mimeType, quality);
                }

                finalBlob = dataURLtoBlob(compressedDataUrl);
                updateUIWithResult(compressedDataUrl, finalBlob, mimeType);
                compressBtn.disabled = false;
                compressBtn.innerHTML = '<svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path d="m15 9-2.5-2.5L10 9l-1.5-1.5L6 10l2.5 2.5L6 15l1.5 1.5L10 14l2.5 2.5L15 14l-2.5-2.5L15 9zm-9 3-2.5-2.5L6 7l1.5 1.5L5 11l2.5 2.5L5 16l-1.5-1.5L6 12zm12 0-2.5-2.5L18 7l1.5 1.5L17 11l2.5 2.5L17 16l-1.5-1.5L18 12z"/></svg>Compress';
            };
        };
    };

    // --- UI Update Functions ---
    const updateUIWithResult = (dataUrl, blob, mimeType) => {
        compressedPreview.src = dataUrl;
        compressedPlaceholder.style.display = 'none';
        compressedPreview.style.display = 'block';
        compressedInfo.style.display = 'block';

        compressedSize.textContent = formatBytes(blob.size);
        compressedSize.classList.toggle('highlight', blob.size < originalImageFile.size);

        downloadBtn.href = dataUrl;
        const fileExtension = mimeType.split('/')[1];
        const originalName = originalImageFile.name.split('.').slice(0, -1).join('.');
        downloadBtn.download = `${originalName}-compressed.${fileExtension}`;
        downloadBtn.style.display = 'inline-flex';
    };

    const handleFileSelect = (file) => {
        if (!file || !file.type.startsWith('image/')) {
            alert('Please select a valid image file (JPG, PNG, WebP).');
            return;
        }
        resetUI(true); // Soft reset
        originalImageFile = file;
        
        const reader = new FileReader();
        reader.readAsDataURL(file);
        reader.onload = (e) => {
            originalPreview.src = e.target.result;
            const img = new Image();
            img.src = e.target.result;
            img.onload = () => {
                originalImageWidth = img.width;
                originalImageHeight = img.height;
                widthInput.value = originalImageWidth;
                heightInput.value = originalImageHeight;
                originalSize.textContent = formatBytes(file.size);
                uploadArea.style.display = 'none';
                processingSection.style.display = 'block';
            };
        };
    };

    const resetUI = (isSoft = false) => {
        if (!isSoft) {
            uploadArea.style.display = 'block';
            processingSection.style.display = 'none';
            fileInput.value = '';
            originalImageFile = null;
            originalPreview.src = '';
            maxSizeInput.value = '';
        }
        compressedPreview.src = '';
        compressedPreview.style.display = 'none';
        compressedPlaceholder.style.display = 'flex';
        compressedInfo.style.display = 'none';
        downloadBtn.style.display = 'none';
    };

    // --- Event Listeners ---
    uploadArea.addEventListener('click', () => fileInput.click());
    uploadArea.addEventListener('dragover', (e) => { e.preventDefault(); uploadArea.classList.add('drag-over'); });
    uploadArea.addEventListener('dragleave', () => uploadArea.classList.remove('drag-over'));
    uploadArea.addEventListener('drop', (e) => { e.preventDefault(); uploadArea.classList.remove('drag-over'); handleFileSelect(e.dataTransfer.files[0]); });
    fileInput.addEventListener('change', (e) => handleFileSelect(e.target.files[0]));

    compressBtn.addEventListener('click', compressImage);
    resetBtn.addEventListener('click', () => resetUI(false));

    qualitySlider.addEventListener('input', () => {
        qualityValue.textContent = parseFloat(qualitySlider.value).toFixed(2);
    });

    widthInput.addEventListener('input', () => {
        if (aspectRatioLock.checked && originalImageWidth > 0) {
            const newHeight = Math.round((widthInput.value / originalImageWidth) * originalImageHeight);
            if (!isNaN(newHeight) && newHeight > 0) heightInput.value = newHeight;
        }
    });

    heightInput.addEventListener('input', () => {
        if (aspectRatioLock.checked && originalImageHeight > 0) {
            const newWidth = Math.round((heightInput.value / originalImageHeight) * originalImageWidth);
            if (!isNaN(newWidth) && newWidth > 0) widthInput.value = newWidth;
        }
    });
    
    formatSelect.addEventListener('change', () => {
        const isPng = formatSelect.value === 'png';
        qualitySlider.disabled = isPng;
        maxSizeInput.disabled = isPng;
        if(isPng) {
            qualitySlider.style.opacity = '0.5';
            maxSizeInput.style.opacity = '0.5';
        } else {
            qualitySlider.style.opacity = '1';
            maxSizeInput.style.opacity = '1';
        }
    });
});
</script>

</body>
</html>
