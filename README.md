# Runtime-Firebase-Initializer
An Android module to initialize Firebase and Crashlytics at runtime, allowing dynamic selection of the Firebase project to use and enabling or disabling Crashlytics.

This approach is useful for separating environments (e.g., test, production) without having to create different builds of the app, especially in IoT or B2B contexts where the configuration may depend on hardware or the tenant.
