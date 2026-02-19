# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0] - 2026-02-17

### Renamed
- **Project Name**: ReelForge → ClipFlow (电影工坊)
  - New ASCII art logo
  - Updated all documentation references

### Added
- **9-Step Workflow**: Complete video creation workflow (upload → analyze → template → generate → dedup → uniqueness → edit → timeline → export)
- **8 Dedup Variants**: Conservative, Balanced, Aggressive, Creative, Academic, Casual, Poetic, Technical
- **Auto Dedup**: Automatic variant selection based on similarity, no user intervention needed
- **Uniqueness Service**: Content fingerprinting + history comparison + auto-rewrite
- **Originality Detection**: Exact match, semantic similarity, template detection, structural duplication
- **Vision Service**: Advanced scene detection, object detection (10 classes), 5-dimension emotion analysis
- **Script Templates**: 7 professional templates (product review, tutorial, knowledge, story, news, entertainment, vlog)
- **Workflow Service**: Orchestrates complete workflow with automatic scene-script matching

### Updated
- **LLM Models (2026 Latest)**:
  - Baidu ERNIE 5.0 (2026-01)
  - Alibaba Qwen 3.5 (2026-01)
  - Moonshot Kimi k2.5 (2025-07)
  - Zhipu GLM-5 (2026-01)
  - MiniMax M2.5 (2025-12)
- **Constants**: Centralized LLM_MODELS with accurate pricing and capabilities
- **AI Service**: Model recommendation and info query methods
- **ModelSelector**: Updated to use new model configuration

### Technical
- Added `useWorkflow` hook for workflow state management
- Added `dedup.templates.ts` with 4 detection strategies
- Added `dedup.variants.ts` with 8 rewrite strategies
- Added `uniqueness.service.ts` for content fingerprinting
- Added `vision.service.ts` for video analysis
- Added `workflow.service.ts` for workflow orchestration

## [1.0.0] - 2026-02-17

### Added
- Initial release of ReelForge
- AI-powered video content creation platform
- Support for 8 major AI providers (OpenAI, Anthropic, Google, Baidu, Alibaba, Zhipu, iFlytek, Tencent)
- Professional video upload and analysis
- AI script generation with multiple styles and tones
- Video export with subtitle support
- Multi-language support (Chinese, English)
- Dark mode support
- Local storage management
- FFmpeg integration for video processing

### Features
- **Model Selector**: Smart AI model selection with cost estimation
- **Video Uploader**: Drag-and-drop upload with preview
- **Script Generator**: AI-powered script generation with customization
- **Project Management**: Complete project lifecycle management
- **Storage Service**: Persistent local storage for projects and settings

### Technical
- React 18 + TypeScript + Vite
- Ant Design 5 + Framer Motion
- Tauri for desktop application
- Zustand for state management
- Modular architecture with service layer

## [0.1.0] - 2026-02-16

### Added
- Project initialization
- Basic project structure
- TypeScript configuration
- Development environment setup
