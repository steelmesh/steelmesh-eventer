# Steelmesh Distributed Event Management Addin

This addin is a websocket driven (via [Socket.IO](http://socket.io/)) event distribution framework.  Eventer enables distributed communication of application messages for web apps that make use of the [eve](http://dmitry.baranovskiy.com/eve/) event library.

## Client Usage (Hosted Service)

An application can utilize event distribution and state management through communication via the [eventer.steelmesh.io](http://eventer.steelmesh.io/) hosted service.

To enable eventer to marshal events for your application first include the eventer library into your application:

```html
<script src="http://eventer.steelmesh.io/api/0.1/eventer.js"></script>
```

This will provide access to the functions outlined in the eventer API, and eventer will by default attempt to wire itself up to eve to marshall messages back to the eventer server.

## Client Usage (Attaching to Your Own Service)

To be completed

## Customizing Message Passing

By default, eventer simply hooks into eve's event handling and looks to handle all events that are passed through.  While in this might be appropriate for some cases, it is probable that if you are using eve extensively, you may want to be more selective about which messages are passed around.

For this, we need to do a little configuration.

### Listening for Specific Eve Messages

To be completed.

### Ignoring particular messages

To be completed.

## Using Eventer without Eve

To be completed.