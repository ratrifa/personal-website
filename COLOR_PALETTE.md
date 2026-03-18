# Color Palette - Satria Febry Personal Website

## Primary Colors

### Background
- **Deep Navy**: `#0a0a1a` - Main background color untuk seluruh website
- **Secondary Navy**: `#1e1b4b` - Digunakan untuk gradient backgrounds dan overlays

### Accent Colors
- **Primary Violet**: `#8b5cf6` - Main accent color untuk buttons, links, dan highlights
- **Secondary Indigo**: `#6366f1` - Digunakan dalam gradients dan hover states
- **Light Violet**: `#a78bfa` - Untuk text highlights dan lighter elements
- **Very Light Violet**: `#c4b5fd` - Subtle accents dan borders

## Text Colors

- **Primary Text**: `#e2e8f0` - Main heading dan body text yang dominan
- **Secondary Text**: `#94a3b8` - Subtitle dan secondary information
- **Tertiary Text**: `#64748b` - Keterangan dan teks yang lebih subtle

## Status & Special Colors

- **Status Yellow/Amber**: `#fbbf24` - Untuk status "In Progress"
- **Status Green**: `#22c55e` - Untuk status "Completed"

## Borders & Overlays

- **Violet Border**: `rgba(139, 92, 246, 0.1)` - Subtle borders
- **Violet Border Hover**: `rgba(139, 92, 246, 0.2-0.3)` - Border pada hover state

## Design System

### Typography
- **Font Family**: Inter (sans-serif)
- **Primary Color**: #a78bfa (violet untuk links dan accents)
- **Background**: #0a0a1a (deep navy)
- **Text**: #e2e8f0 (light slate)

### Spacing System
- Menggunakan Tailwind spacing scale: 0.25rem (4px), 0.5rem (8px), 1rem (16px), dll.

### Border Radius
- Cards & Components: 12px - 20px
- Buttons: 8px - 12px
- Images: 50% (circular), 12px - 16px (rounded)

### Shadows
- Subtle: `0 4px 20px rgba(139, 92, 246, 0.15)`
- Medium: `0 8px 30px rgba(139, 92, 246, 0.2-0.4)`
- Large: `0 25px 50px rgba(0, 0, 0, 0.4)`

### Gradients
- **Primary Gradient**: `linear-gradient(135deg, #8b5cf6 0%, #6366f1 100%)` - Buttons, CTA
- **Hero Gradient**: `linear-gradient(180deg, #0a0a1a 0%, #1e1b4b 50%, #0a0a1a 100%)` - Hero section background
- **Text Gradient**: `linear-gradient(135deg, #a78bfa 0%, #818cf8 50%, #c4b5fd 100%)` - Highlight text

## Usage Guide

### Hero Section
- Background: Deep Navy dengan gradient accent
- Text: Light Slate dengan Violet highlights
- Buttons: Gradient Violet to Indigo

### Project Cards
- Background: Transparent dengan Navy overlay (rgba)
- Border: Violet dengan 0.15 opacity
- Hover: Border opacity meningkat ke 0.3
- Text: Light Slate dengan Violet accents

### Contact Form
- Background: Navy dengan Violet border
- Input: Dark Navy background dengan Violet focus state
- Button: Gradient Violet to Indigo dengan shadow

### Status Indicators
- In Progress: #fbbf24 (Amber)
- Completed: #22c55e (Green)
