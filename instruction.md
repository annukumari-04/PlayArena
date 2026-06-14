# Create a Browser-Based Gaming Platform - PlayArena

# Context

Create a modern browser-based gaming platform that allows visitors to instantly discover and play a curated collection of HTML5 games directly from their browser.

The platform should combine the simplicity of modern gaming portals with lightweight progression systems that encourage repeat visits.

Users must be able to start playing immediately without creating an account.

The platform should support optional account creation for users who want to permanently save their progress, synchronize data across devices, and participate in leaderboard competitions.

All integrated games must be:
- Properly licensed
- Open-source
- Royalty-free
- Client-owned or legally distributable

---

# Goal

Create a gaming platform where users can:

1. Play games instantly without registration.
2. Earn virtual gold coins through gameplay.
3. Save progress locally as a guest.
4. Create an account to permanently save progress.
5. Sync guest progress after registration.
6. Unlock games using earned coins.
7. Receive daily game recommendations.
8. Collect achievement badges.
9. Participate in weekly leaderboard competitions.
10. Track progress through a personal dashboard.

---

# Branding Requirements

I will provide the official PlayArena logo and branding assets.

Requirements:

* Use only the provided PlayArena logo throughout the platform.
* Display the logo consistently across the homepage, navigation bar, authentication pages, user dashboard, admin dashboard, footer, and favicon where applicable.
* Maintain consistent branding across all pages and user experiences.
* The logo should remain recognizable and should not be altered beyond standard sizing and responsive adjustments.

Not Required:

* Logo design
* Logo redesign
* Logo recreation
* Brand identity development
* Alternative logo concepts
* Custom illustrations based on the logo

The developer should integrate and optimize the provided branding assets but should not modify the brand identity.

# Platform Structure Requirements

The platform must include:

## Public Website

- Homepage
- Browse Games Page
- Category Pages
- Individual Game Pages
- Login Page
- Registration Page
- Weekly Leaderboard Page
- Favorites Page
- Recently Played Page

## User Dashboard

### Guest Dashboard

Include:
- Coin balance
- Daily rewards
- Recently played games
- Continue playing section
- Favorite games
- Achievement badges

### Registered Dashboard

Include:
- User profile
- Coin wallet
- Coin history
- Daily rewards
- Recently played games
- Continue playing section
- Recommended games
- Favorite games
- Achievement badges
- Unlocked games library
- Leaderboard ranking

---

# Game Catalog Requirements

The platform should support:

- 50–100 HTML5 games
- Multiple game categories
- Search functionality
- Favorites
- Recently played tracking
- Continue playing functionality

Daily Rotation:

- 25–30 games featured daily
- Featured games rotate automatically from the catalog
- Recommendations adapt to player activity

Requirements:

- Fullscreen gameplay
- Embedded browser gameplay
- Mobile-friendly experience
- Fast loading experience

---

# Guest First Experience

Visitors should be able to:

- Play games immediately
- Earn coins
- Unlock achievements
- Save favorites
- Track recently played games
- Receive daily rewards

Guest progress should be stored using browser local storage.

After meaningful engagement, users may be prompted to create an account.

Benefits of registration:

- Cloud save
- Progress synchronization
- Multi-device access
- Leaderboard participation
- Achievement backup

Avoid:

- Mandatory login before gameplay
- Forced registration
- Login walls

---

# Homepage Requirements

## Hero Section

Include:

- Platform branding
- Main headline
- Call-to-action button
- Featured game highlight

## Daily Games Section

Display:

- Daily featured games
- Game thumbnails
- Coin rewards

## Continue Playing

Display:

- Previously played games
- Resume gameplay buttons

## Recommended For You

Display:

- Personalized recommendations
- Preferred categories
- Recently played genres

## Weekly Leaderboard

Display:

- Top players
- Weekly rankings
- Coins earned

## Daily Rewards

Display:

- Daily login reward
- Current streak
- Reward information

---

# Coin Economy Requirements

Users should earn coins through:

- Playing games
- Completing games
- Daily rewards
- Achievement milestones

Users should spend coins on:

- Unlocking games
- Unlocking premium content sections

Requirements:

- Coin balances tracked securely
- Transactions recorded
- Validated coin deductions

---

# Recommendation System Requirements

Track:

- Gameplay history
- Category preferences
- Engagement levels
- Game popularity

Recommendations should:

- Refresh daily
- Adapt to behavior
- Promote discovery
- Avoid repetitive suggestions

Simple rule-based recommendations are acceptable.

---

# Weekly Leaderboard Requirements

Leaderboard must:

- Rank users by coins earned
- Reset automatically each week
- Display player rankings
- Reward top performers

Display:

- Username
- Rank
- Coins earned
- Games played

---

# Admin Dashboard Requirements

## Authentication

Include:

- Secure admin login
- Session management

## Game Management

Include:

- Add games
- Edit games
- Remove games
- Manage categories
- Configure coin rewards
- Configure unlock costs
- Manage daily rotations

## User Management

Include:

- View users
- View statistics
- View coin balances

---

# Technical Requirements

The solution must include:

- Responsive design
- Mobile-friendly layouts
- Cross-browser compatibility
- Secure authentication
- Database-backed user management
- Coin transaction tracking
- Optimized performance
- Clean code structure
- Deployment-ready configuration

Recommended Stack:

Frontend:
- React
- Vite
- Tailwind CSS

Backend:
- Supabase Authentication
- Supabase Database

Equivalent technologies are acceptable.

---

# Design Requirements

Visual Style:

- Modern
- Clean
- Engaging
- Game-focused
- Beginner-friendly

Avoid:

- Cluttered layouts
- Excessive animations
- Overly complex interfaces

---

# Content Requirements

The platform must:

- Use short, readable content
- Prioritize game discovery
- Support quick navigation
- Maintain visual consistency

Avoid:

- Long text blocks
- Unnecessary onboarding flows

---

# Visual Requirements

Use visuals to support gameplay discovery.

Allowed:

- Game thumbnails
- Category icons
- Achievement icons
- Leaderboard visuals
- Minimal illustrations

Not Allowed:

- Copyrighted assets
- Watermarked assets
- Unlicensed visuals

---

# Reference Asset Restrictions

Any reference images, screenshots, wireframes, UI examples, logos, or website inspirations provided with this task are for reference purposes only.

## Requirements:

-Use references only to understand functionality, layout direction, visual style, and user experience expectations.
-Create original designs, layouts, graphics, and implementations.
-Do not directly copy, recreate, trace, or replicate any provided reference material.
-Do not reproduce copyrighted elements, branding, artwork, or proprietary designs from reference sources.

The final deliverable must be an original implementation inspired by the requirements rather than a duplicate of any reference material.

# Deliverables

## Web Application

Include:

- Frontend application
- Backend application
- Database schema
- Configuration files

## Documentation

Include:

- Installation guide
- Deployment guide
- Admin guide

---

# Required Delivery Structure

GamingPlatform/

├── Frontend/
├── Backend/
├── Database/
├── Documentation/
└── Assets/

---

# Scope Restrictions

Do NOT include:

- Real-money gaming
- Gambling mechanics
- Multiplayer gameplay
- Chat systems
- Voice communication
- Cryptocurrency integration
- NFT functionality
- Payment gateways
- Advanced AI models

---

# Acceptance Criteria

1. Games load and play in browser.
2. Guest users can play without registration.
3. Progress sync works after registration.
4. Coins are awarded correctly.
5. Daily featured games rotate.
6. Favorites and recently played work correctly.
7. Leaderboard updates correctly.
8. Admin dashboard manages games successfully.
9. Responsive layouts function across devices.
10. No critical console errors.

---

# Final Goal

The final result should function as a lightweight gaming ecosystem that combines:

- Instant gameplay
- Daily game discovery
- Virtual rewards
- Achievement progression
- Personalized recommendations
- Competitive leaderboards

Users should be encouraged to return regularly through rewards, progression systems, and rotating game selections.