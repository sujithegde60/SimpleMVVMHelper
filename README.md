# MVVMHelper

**MVVMHelper** is a lightweight utility library designed to simplify the implementation of the MVVM pattern in .NET applications. It provides two essential components: `ChangeNotifier` and `RelayCommand`.

## Features

- **ChangeNotifier**:
  - Implements `INotifyPropertyChanged`.
  - Simplifies property change notification for view models.
  
- **RelayCommand**:
  - Implements the `ICommand` interface.
  - Supports parameterized commands and `CanExecute` logic.
  - Allows manual triggering of `CanExecuteChanged`.

## Installation

Install via NuGet Package Manager:

```bash
Install-Package SimpleMVVMHelper -Version 1.0.1
