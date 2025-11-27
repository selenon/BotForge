#BotForge

BotForge provides an end-to-end solution for building intelligent customer support chatbots. With support for both text and voice interactions, 3D avatar integration, and customizable templates, businesses can create engaging support experiences that align with their brand identity.

## Core Features

- **Website Integration**: Embed chatbots using simple code snippets or direct links
- **Customizable Templates**: Pre-built templates for various support scenarios
- **3D Avatar Interface**: Interactive 3D characters for engaging user interactions
- **Dual-Mode Interaction**: Support for both text and voice input/output
- **Knowledge Base Integration**: Connect your documentation and support materials
- **Vector-Based Storage**: Efficient conversation data handling with MongoDB Atlas

## Technical Architecture

### Backend Stack
- **Node.js & Express**: API server and request handling
- **MongoDB Atlas**: Data storage with vector support for similarity search
- **Language Models**: Integration with Mistral and Llama for natural language processing
- **WebSocket Support**: Real-time communication for live interactions

### Frontend Stack
- **React**: Responsive user interface components
- **Three.js**: 3D avatar rendering and animation
- **Web Audio API**: Voice input and output processing
- **Embeddable Widget**: Lightweight integration script for websites

## Integration Process

1. **Create Chatbot**: Configure your chatbot through the BotForge web interface
2. **Customize Appearance**: Select templates and adjust branding elements
3. **Add Knowledge**: Upload support documents and training materials
4. **Generate Code**: Receive embeddable code snippet for your website
5. **Deploy**: Add the code to your website's HTML

## Key Functionality

### Chat Interface
- Text-based queries with instant responses
- Voice input with speech recognition
- Multi-modal responses (text + audio)
- Conversation history and context maintenance

### Template System
- Industry-specific conversation flows
- Customizable response patterns
- Brand-aligned visual themes
- Pre-built support scenarios

### Avatar Customization
- Multiple character options
- Adjustable visual styles
- Brand-specific customization
- Responsive animations

## Development Roadmap

- **Model Selection**: Choose between different language model providers
- **Analytics Dashboard**: Track performance metrics and user engagement
- **Advanced Customization**: More granular control over avatar behavior
- **Learning Systems**: AI that improves from conversation history
- **Multi-language Support**: Expanded language options

## Getting Started

### Backend Setup

```bash
git clone https://github.com/selenon/BotForge.git
cd BotForge
npm install
```

Create a `.env` file with required variables:

```
MONGODB_URI=your_mongodb_connection_string
GROQ_API_KEY=your_groq_api_key
COHERE_API_KEY=your_cohere_api_key
```

Start the development server:

```bash
npm run dev
```

### Frontend Testing

1. Navigate to the frontend directory
2. Open `index.html` in your browser or use a local server
3. Generate your chatbot through the web interface
4. Replace the demo chatbot element with your generated code
5. Test the integration locally

### Voice Features

Enable text-to-speech functionality by appending `/tts` to your chatbot URL in the embed code:

```html
<iframe src="your-chatbot-url/tts" ...></iframe>
```

## Usage

1. **Sign Up**: Create an account on the BotForge platform
2. **Configure**: Set up your chatbot using the configuration dashboard
3. **Train**: Add your knowledge base and training materials
4. **Customize**: Adjust appearance and behavior settings
5. **Deploy**: Copy the generated code to your website
6. **Monitor**: Track performance and user interactions

## Support

For technical support and documentation, visit our support portal or check the documentation included in the repository.
