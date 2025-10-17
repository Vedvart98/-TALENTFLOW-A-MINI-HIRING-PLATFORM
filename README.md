# TalentFlow - Mini Hiring Platform

A modern, React-based hiring platform for managing candidates, jobs, and assessments with an intuitive drag-and-drop interface.

## 🚀 Features

- **Candidate Management**: Track 1000+ candidates through hiring stages
- **Drag & Drop Interface**: Move candidates between hiring stages seamlessly  
- **Job Management**: Create, edit, and manage job postings
- **Assessment Builder**: Build custom assessments for different roles
- **Real-time Updates**: Live candidate status tracking
- **Notes & Timeline**: Add notes and track candidate progress
- **Responsive Design**: Works on desktop and mobile devices

## 🛠️ Tech Stack

- **Frontend**: React 18, Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Drag & Drop**: @dnd-kit
- **Database**: IndexedDB (Dexie.js)
- **Notifications**: React Toastify
- **Routing**: React Router DOM

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/Vedvart98/-TALENTFLOW-A-MINI-HIRING-PLATFORM.git
cd talentflow-hiring-platform
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm run dev
```

4. **Open in browser**
```
http://localhost:5173
```

## 🔐 Login Credentials

- **Email**: `extnt@hr.in`
- **Password**: `123456`

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Main application pages
├── context/            # React context for state management
├── database/           # IndexedDB setup and seeding
├── hooks/              # Custom React hooks
├── mocks/              # API mocking with MSW
├── services/           # API service layer
└── assets/             # Static assets and icons
```

## 🎯 Key Pages

- **Dashboard**: Overview of hiring metrics
- **Jobs Board**: Manage job postings
- **Candidates Board**: Kanban-style candidate management
- **Assessments**: Create and manage assessments
- **Candidate Detail**: Individual candidate profiles

## 🗄️ Data Management

The application uses:
- **IndexedDB** for persistent storage
- **localStorage** for backup and caching
- **Mock Service Worker** for API simulation
- **Deterministic data generation** for 1000 sample candidates

## 🚀 Available Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Run ESLint
```

## 🎨 Hiring Stages

1. **Applied** - Initial application received
2. **Online Assessment** - Candidate taking online test
3. **Technical Interview** - Technical screening
4. **Final Interview** - Final round with management
5. **Hired** - Candidate accepted
6. **Rejected** - Application declined

## 🔧 Configuration

The app automatically seeds with:
- 25 sample job postings
- 1000 generated candidates
- 3 assessment templates
- Complete hiring pipeline data

## 📱 Responsive Design

- Mobile-first approach
- Optimized for tablets and desktops
- Touch-friendly drag and drop
- Collapsible navigation

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License.

## 🙋‍♂️ Support

For support or questions, please open an issue in the GitHub repository.

---

**Built with ❤️ for modern hiring teams**# -TALENTFLOW-A-MINI-HIRING-PLATFORM
# -TALENTFLOW-A-MINI-HIRING-PLATFORM
