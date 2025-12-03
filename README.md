# Blogging System - Real-World Django Project
This blogging platform is designed as a comprehensive, feature-rich blogging system built with Django, incorporating essential features commonly used in real-world applications. From models and templates to permissions, dashboards, and deployment.

## Features

### User Roles and Permissions
#### Multi-role System with distinct access levels:
	- Admin: Full access to all parts of the system.
	- Manager: Can manage posts and categories.
	- Editor: Can edit posts and approve content.
	- Author: Can create and manage their own posts.

#### Granular Permissions:
	- Utilizes Django Groups & Permissions to implement role-specific access.
	- Custom permission checks to restrict access where necessary.

### Content Management
#### Create, Read, Update, Delete (CRUD) operations for:
	- Posts: Authors, Editors, and Managers can create, edit, and delete posts.
	- Categories: Admin and Manager roles can manage categories.

#### Unique Slug Generation:
	- Automatically generates slugs for posts and categories.
	- Prepopulation of slugs based on post titles for consistency.

### Media Handling
#### Image Upload & Configuration:
	- Built-in functionality for uploading images to posts.
	- Configuration to handle and serve media files effectively.

### Interactive Features
#### Comment System:
	- Only authenticated users can leave comments on posts.
	- Ensures community engagement while maintaining security.

### Dashboards
#### Manager & Editor Dashboards:
	- Includes useful counts and tables for posts, comments, and categories, making it easy to manage content.

### Search Functionality
#### Search Feature:
	- Enables users to search for posts.
	- Retains search terms in the textbox for user convenience.

### Deployment
#### Deployed on PythonAnywhere:
	- The project is fully deployed and live on PythonAnywhere, showcasing a production-ready environment for Django apps.
