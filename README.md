# Parse SDK for JavaScript

temporary build to fix the React-Native 0.44 issue:

change line in file lib/react-native/StorageController.react-native.js from:

import { AsyncStorage } from 'react-native/Libraries/react-native/react-native.js';

to

import { AsyncStorage } from '../../../react-native';
