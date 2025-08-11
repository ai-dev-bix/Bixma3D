# WalkTheWeb - Functional Mapping

## Core Features → Code Mapping

### 1. User Authentication & Management
- **Files**: 
  - `connect/user.php` - User operations
  - `connect/useraccess.php` - Access control
  - `connect/userauthenticate.php` - Authentication
  - `connect/userprofile.php` - Profile management
  - `connect/users.php` - User listing
- **Classes**: TBD (need to analyze core classes)

### 2. Avatar System
- **Files**:
  - `connect/avatar.php` - Avatar operations
  - `connect/avatars.php` - Avatar listing
  - `connect/avataranimations.php` - Animation system
  - `connect/useravatar.php` - User-avatar association
  - `content/plugins/wtw-avatars/` - Avatar plugin
- **3D Assets**: Avatar models and animations

### 3. 3D Environment Management
- **Files**:
  - `connect/building.php` - Building operations
  - `connect/buildings.php` - Building listing
  - `connect/community.php` - Community spaces
  - `connect/communities.php` - Community listing
  - `connect/thing.php` - 3D object operations
  - `connect/things.php` - 3D object listing
- **3D Assets**: `.babylon` files in various directories

### 4. Web/Domain Management
- **Files**:
  - `connect/webs.php` - Web space management
  - `connect/webdomain.php` - Domain operations
  - `connect/webdomains.php` - Domain listing
  - `connect/webalias.php` - Alias management
  - `connect/webaliases.php` - Alias listing

### 5. Plugin System
- **Core**: `core/functions/class_wtwplugins.php`
- **Plugins**:
  - `wtw-3dinternet` - Core 3D functionality
  - `wtw-avatars` - Avatar management
  - `wtw-coins` - Virtual currency
  - `wtw-shopping` - E-commerce
  - `wtw-swiftmailer` - Email system

### 6. 3D Interaction Systems
- **Movement**: Movement controls and physics
- **Voice Chat**: Real-time communication
- **Action Zones**: Interactive 3D areas
- **Object Interactions**: 3D object manipulation

## TBD - Needs Deep Analysis
- Core class hierarchy
- Database schema
- 3D scene management
- Babylon.js integration patterns
- Plugin API structure