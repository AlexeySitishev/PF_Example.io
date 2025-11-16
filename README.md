# MCC Configuration Tool

A self-contained, interactive web application for configuring Merchant Category Code (MCC) and product processing fees. Designed for easy embedding in Confluence pages.

## 📁 Files Included

1. **mcc-configuration.html** (Main application)
   - Complete, self-contained HTML file
   - No external dependencies
   - Ready for Confluence embedding
   - Size: ~35KB

2. **CONFLUENCE-INSTRUCTIONS.md** (Detailed embedding guide)
   - Step-by-step instructions for 3 embedding methods
   - Troubleshooting guide
   - Feature documentation

3. **README.md** (This file)
   - Quick overview

## 🚀 Quick Start

### For Confluence (Simplest Method):

1. Edit your Confluence page
2. Type `/html` and select "HTML" macro
3. Copy & paste the entire contents of `mcc-configuration.html`
4. Save

That's it! 🎉

### If the above doesn't work (security restrictions):

See `CONFLUENCE-INSTRUCTIONS.md` for alternative embedding methods using iframes.

## ✨ Features

- **MCC Selection**: Choose between Default or Fashion
- **Product Configuration**: Enable/disable 4 products (Postpaid, 3/7/11 months)
- **Grab Bundle Toggle**: ON/OFF per product
- **PF Waiver Selector**: 0%, 20%, 40%, 60%, 80%, 100%
- **Auto-calculated Processing Fees**: Based on waiver mapping
- **Live Summary**: Real-time configuration overview
- **JSON Export**: Copy configuration to clipboard
- **Reset Function**: Restore defaults anytime

## 📊 PF Waiver to Processing Fee Mapping

| PF Waiver | Processing Fee |
|-----------|----------------|
| 0%        | 1.5%           |
| 20%       | 1.2%           |
| 40%       | 0.9%           |
| 60%       | 0.6%           |
| 80%       | 0.3%           |
| 100%      | 0%             |

## 🔒 Security

- ✅ No external dependencies
- ✅ No API calls
- ✅ No data collection
- ✅ All processing happens client-side
- ✅ Safe for sensitive data

## 🌐 Browser Support

- ✅ Chrome/Edge
- ✅ Firefox
- ✅ Safari
- ❌ IE11 (not supported)

## 📖 Documentation

For detailed embedding instructions, troubleshooting, and feature descriptions, see:
- `CONFLUENCE-INSTRUCTIONS.md`

## 💡 Tips

1. **Test first**: Try Option 1 (HTML macro) first as it's the simplest
2. **Adjust iframe height**: If using iframe, adjust height to fit your content (default: 1200px)
3. **JSON export**: Use the "Copy JSON" button to share configurations
4. **Reset anytime**: Use "Reset to Defaults" to start over

## 🎯 Use Cases

- Configure product processing fees by MCC
- Experiment with different bundle and waiver combinations
- Export configurations for documentation
- Share configurations via JSON

## 📝 Version

- **Version**: 1.0.0
- **Date**: November 14, 2025
- **Status**: Production Ready ✅

---

**Need help?** Check `CONFLUENCE-INSTRUCTIONS.md` for detailed guidance.

