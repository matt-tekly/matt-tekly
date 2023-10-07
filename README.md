# Hello!
I'm a game developer with 10+ years of Unity experience. I enjoy making scalable and reusable code.

# Tekly
Tools for creating games in Unity

## Tekly Packages
Several [open source packages](https://github.com/matt-tekly/tekly-packages) that handle some of the fundamentals of game development.

The packages include

- Tekly Basic Builder: A simple configurable window for making Player Builds
- Tekly Common: Provides common utilities for use in Unity and in the Tekly Packages
- Tekly Content: A basic wrapper around Addressables that makes the API slightly nicer
- Tekly DataModel: A data binder system for making UI. Create data models that can be reactively bound to UI components
  - Create data model classes that have named properties and binders can bind to the properties based on string paths to those properties
  - Binders are MonoBehaviours that take a path to a DataModel and then configure some UI component with the data from the model
  - Extremely useful for making UI that UI artists can hook up themselves
- Tekly Favorites: A tool window for quickly accessing commonly used assets or GameObjects
- Tekly Injectors: Basic dependency injection. Can be used for plain C# objects but has components for very efficiently injecting into GameObjects.
- Tekly Localizations: WIP localization system. It is functional but will change with improvements over time
- Tekly Logger: A powerful logging solution to replace Debug.Log
- Tekly Sheets: Downloads Google Sheets and turns them into JSON or Scriptable Objects
- Tekly TreeState: A hierarchical state machine that is defined with GameObjects and custom behaviours
  - This is used to model the state of your game rather than the state of entity
  - Handles transitioning between states and coordinating loading and unloading
  - You create behaviours that are attached to states and the behaviours are active if their state is active
  - Has excellent but optional integration with Tekly Injectors
- Tekly Webster: A powerful tool for remote debugging your game
  - Webster embeds a web server in your game and provides a web interface to controlling your game and retrieving information about the game
  - Remotely connect to a player build
  - View the contents of the disk
  - View the GameObject hierarchy, enable and disable GameObjects or Components
  - View all loaded Assets
  - Frameline: A timeline view of user defined events
  - Execute functions from a simple to use interface

