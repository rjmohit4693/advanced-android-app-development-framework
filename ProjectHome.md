The Advanced Android App Development Framework is a project to bring the Model-View-Controller philosophy to Android.

http://en.wikipedia.org/wiki/Model-view-controller

While attempts have been made in the past, the A3D Framework will take a different approach:

Instead of aiming to completely rewrite the Android app UI and logic code, the A3D Framework aims to provide developers with a compliment of convenience and wrapper classes that will make it easier to develop content-rich apps, including classes for abstracting database creation and access based on Java data structures, and a simpler, more modular coupling of UI and app logic code.

The A3D Framework will also provide access to the Android Query library as well as some convenience methods for simpler AJAX coding.

The A3D Framework will work to emulate the Model-View-Controller in an environment where the View is already provided, but lacking in structured data representation.

The Controller will be a bound service whose implementation details are abstracted so that the user only need be concerned with the logic code itself and won't have to bother with any of the boilerplate stuff that ends up being the source of so many bugs.

The Model will be represented by an abstract data structure class, where the developer only need supply the names and native Java types of the data they intend to store, and the table is created for them. Any custom class is welcome as long as it implements Serializable.

The View will be an extended and abstracted Activity/Fragment coupling. Transactions and lifecycle callbacks are a thing of the past. You only need supply the name of the fragment and the resource ID of the layout to instantiate, and the rest is taken care of. Specific view types and data types, like a TextView and String, respectively, are automatically linked based on name alone. More convenient Adapter implementations for ListViews and Spinners are also in the works.

The project itself is welcome to contribution and criticism. This is meant to make it easier for everyone.