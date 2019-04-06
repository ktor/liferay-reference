# liferay-reference
The project serves as an index of Liferay CE 7 code. It's meant to include all Liferay 7 code as dependency.
 
## Usage
It's meant to be opened with an IDE that supports maven an can index all dependencies together with sources like Intellij IDEA for example.
 
Once imported user can leverage all IDE tools like Intellij IDEA [structural search][1], [go to implementation][2], full text search etc. to find API's and sources he's interested in.
  
### Basic facts
* The project uses release.portal.bom artifact from Liferay as a base. 
* The project is not meant to be built. 
* The project contains no own sources.

### Another solution
The project creates IntelliJ IDEA project modules that contains whole Liferay 7 code: https://github.com/holatuwol/liferay-intellij

## Dependencies reference
```bash
[INFO] --- maven-dependency-plugin:2.8:tree (default-cli) @ liferay-reference ---
[INFO] org.synus:liferay-reference:pom:7.1.2.1
[INFO] +- com.liferay.portal:com.liferay.portal.web:war:2.0.123:compile
[INFO] +- com.liferay.plugins:fjord-theme:war:2.0.15:compile
[INFO] +- com.liferay.plugins:porygon-theme:war:2.0.3:compile
[INFO] +- com.liferay.plugins:westeros-bank-theme:war:2.0.13:compile
[INFO] +- com.liferay.plugins:admin-theme:war:2.0.18:compile
[INFO] +- com.liferay.plugins:powwow-portlet:war:7.1.0.18:compile
[INFO] +- com.liferay.plugins:classic-theme:war:2.0.21:compile
[INFO] +- com.liferay.plugins:social-bookmarks-hook:war:7.1.0.3:compile
[INFO] +- com.liferay.plugins:opensocial-portlet:war:7.1.0.19:compile
[INFO] +- com.liferay.plugins:tasks-portlet:war:7.1.0.12:compile
[INFO] +- xdoclet:xdoclet:jar:1.2.3:compile
[INFO] +- xdoclet:xdoclet-web-module:jar:1.2.3:compile
[INFO] +- javax.portlet:portlet-api:jar:3.0.1:compile
[INFO] |  \- javax.enterprise:cdi-api:jar:1.2:compile
[INFO] |     +- javax.el:javax.el-api:jar:3.0.0:compile
[INFO] |     +- javax.interceptor:javax.interceptor-api:jar:1.2:compile
[INFO] |     \- javax.inject:javax.inject:jar:1:compile
[INFO] +- javax.servlet:javax.servlet-api:jar:3.1.0:compile
[INFO] +- jstl:jstl:jar:1.2:compile
[INFO] +- org.osgi:osgi.cmpn:jar:6.0.0:compile
[INFO] +- org.osgi:org.osgi.service.component.annotations:jar:1.3.0:compile
[INFO] +- org.osgi:org.osgi.core:jar:6.0.0:compile
[INFO] +- javax.ws.rs:javax.ws.rs-api:jar:2.1:compile
[INFO] +- org.osgi:org.osgi.service.jaxrs:jar:1.0.0:compile
[INFO] +- biz.aQute.bnd:biz.aQute.bndlib:jar:3.5.0:compile
[INFO] +- com.liferay:com.liferay.portal.tools.target.platform.indexer.client:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.tools.db.upgrade.client:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.iframe.web:jar:2.0.8:compile
[INFO] +- com.liferay:com.liferay.unit.converter.web:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.test.util:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.image.service:jar:2.0.9:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.image.item.selector.api:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.upload:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.image.content.transformer:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.image.api:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.image.impl:jar:2.0.17:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.content.transformer.api:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.content.transformer.impl:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.api:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.image.item.selector.impl:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.item.selector.upload.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.document.library.thumbnails:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.image.content.transformer.backwards.compatibility:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.web:jar:2.0.16:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.document.library:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.demo.data.creator.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.demo.data.creator.impl:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.image.taglib:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.journal.editor.configuration:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.blogs.item.selector.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.image.js.web:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.blogs.editor.configuration:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.blogs.web.fragment:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.document.library.item.selector.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.image.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.document.library.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.blogs.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.adaptive.media.journal.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.scripting.javascript:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.portal.security.audit.storage.api:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.security.audit.event.generators.user.management:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.security.audit.storage.service:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.security.audit.router:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.security.audit.api:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.security.audit.impl:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.security.audit.wiring:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.security.audit.event.generators.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.dependency.factory.impl:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.instances.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.instances.web:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.instances.service:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.module.configuration:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.upgrade.api:jar:1.1.1:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.metatype.definitions.equinox:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.cluster:jar:4.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.upgrade.impl:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.test.util:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.metatype.definitions.annotations:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.extender:jar:4.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.settings:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.image.uploader.web:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.task.web:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.kaleo.definition.impl:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.kaleo.runtime.api:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.kaleo.runtime.impl:jar:3.0.10:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.kaleo.runtime.form.impl:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.kaleo.api:jar:3.2.0:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.lang:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.kaleo.definition.api:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.api:jar:1.2.3:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.kaleo.service:jar:3.0.20:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.kaleo.runtime.integration.impl:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.kaleo.runtime.scripting.impl:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.workflow.web:jar:1.0.23:compile
[INFO] +- com.liferay:com.liferay.license.manager.web:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.scripting.python:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.apio.architect.api:jar:1.8.1:compile
[INFO] +- com.liferay:com.liferay.apio.architect.impl:jar:1.0.17:compile
[INFO] +- com.liferay:com.liferay.apio.architect.uri.mapper.impl:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.apio.architect.exception.mapper.impl:jar:1.0.8:compile
[INFO] +- com.liferay:com.liferay.apio.architect.test.util:jar:1.0.14:compile
[INFO] +- com.liferay:com.liferay.frontend.css.web:jar:2.0.11:compile
[INFO] +- com.liferay:com.liferay.frontend.css.rtl.servlet:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.frontend.css.common:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.journal.content.search.web:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.social.requests.web:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.social.group.statistics.web:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.social.user.statistics.web:jar:4.0.7:compile
[INFO] +- com.liferay:com.liferay.deprecated.modules.upgrade:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.social.activity.web:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.search.elasticsearch6.impl:jar:2.0.35:compile
[INFO] +- com.liferay:com.liferay.portal.search.elasticsearch6.api:jar:2.0.10:compile
[INFO] +- com.liferay:com.liferay.directory.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.dictionary.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.relationship.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.relationship.impl:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.url.builder.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.url.builder.impl:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.websocket.whiteboard:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.lock.service:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.portal.lock.api:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.toolbar.contributor.locator.impl:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.icon.edit:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.icon.refresh:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.icon.minimize:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.icon.help:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.icon.print:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.icon.close:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.icon.maximize:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.icon.edit.defaults:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.icon.edit.guest:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.web:jar:2.0.27:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.icon.locator.impl:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.css.web:jar:3.0.22:compile
[INFO] +- com.liferay:com.liferay.portlet.configuration.sharing.web:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.rules.engine.api:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.rules.engine.wiring:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.contacts.api:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.contacts.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.contacts.web:jar:2.0.16:compile
[INFO] +- com.liferay:com.liferay.contacts.service:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.monitoring.web:jar:2.0.8:compile
[INFO] +- com.liferay:com.liferay.marketplace.store.web:jar:4.0.5:compile
[INFO] +- com.liferay:com.liferay.marketplace.api:jar:5.0.3:compile
[INFO] +- com.liferay:com.liferay.marketplace.app.manager.web:jar:2.0.18:compile
[INFO] +- com.liferay:com.liferay.marketplace.service:jar:4.0.14:compile
[INFO] +- com.liferay:com.liferay.document.library.google.docs:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.polls.web:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.polls.api:jar:5.0.2:compile
[INFO] +- com.liferay:com.liferay.polls.service:jar:4.0.13:compile
[INFO] +- com.liferay:com.liferay.frontend.image.editor.capability.crop:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.frontend.image.editor.integration.document.library:jar:2.0.8:compile
[INFO] +- com.liferay:com.liferay.frontend.image.editor.web:jar:2.0.10:compile
[INFO] +- com.liferay:com.liferay.frontend.image.editor.capability.rotate:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.frontend.image.editor.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.frontend.image.editor.capability.brightness:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.frontend.image.editor.capability.saturation:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.frontend.image.editor.capability.resize:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.frontend.image.editor.capability.contrast:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.frontend.image.editor.capability.effects:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.remote.axis.extender:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.remote.soap.extender.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.remote.jaxrs.whiteboard.jaxb.json:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.remote.soap.extender.impl:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.remote.rest.extender:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.remote.cxf.common:jar:4.0.8:compile
[INFO] +- com.liferay:com.liferay.portal.remote.jaxrs.whiteboard.debug:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.portal.remote.http.whiteboard.debug:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.remote.http.tunnel.extender:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.remote.json.web.service.extender:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.remote.jaxrs.whiteboard:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.search.web.api:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.search:jar:5.0.20:compile
[INFO] +- com.liferay:com.liferay.portal.search.web:jar:3.0.38:compile
[INFO] +- com.liferay:com.liferay.portal.search.test.util:jar:2.1.18:compile
[INFO] +- com.liferay:com.liferay.portal.search.spi:jar:2.1.4:compile
[INFO] +- com.liferay:com.liferay.portal.search.admin.web:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.search.engine.adapter.api:jar:2.2.1:compile
[INFO] +- com.liferay:com.liferay.portal.search.api:jar:2.0.11:compile
[INFO] +- com.liferay:com.liferay.wysiwyg.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.mobile.device.rules.api:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.mobile.device.rules.service:jar:2.0.8:compile
[INFO] +- com.liferay:com.liferay.mobile.device.rules.web:jar:2.0.14:compile
[INFO] +- com.liferay:com.liferay.password.policies.admin.web:jar:2.0.14:compile
[INFO] +- com.liferay:com.liferay.password.policies.admin.api:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.password.policies.admin.impl:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.password.policies.admin.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.rss.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.rss.web:jar:4.0.12:compile
[INFO] +- com.liferay:com.liferay.rss.taglib:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.rss.impl:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.document.library.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.document.library.file.rank.service:jar:1.0.10:compile
[INFO] +- com.liferay:com.liferay.document.library.repository.cmis.impl:jar:3.0.13:compile
[INFO] +- com.liferay:com.liferay.document.library.repository.authorization.api:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.document.library.content.service:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.document.library.web:jar:3.0.40:compile
[INFO] +- com.liferay:com.liferay.document.library.repository.search:jar:4.0.3:compile
[INFO] +- com.liferay:com.liferay.document.library.analytics:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.document.library.content.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.document.library.repository.cmis.api:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.document.library.service:jar:3.0.30:compile
[INFO] +- com.liferay:com.liferay.document.library.file.rank.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.document.library.repository.external.api:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.document.library.sync.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.document.library.api:jar:4.1.3:compile
[INFO] +- com.liferay:com.liferay.document.library.document.conversion:jar:1.0.11:compile
[INFO] +- com.liferay:com.liferay.document.library.layout.set.prototype:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.document.library.test.util:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.document.library.item.selector.web:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.document.library.sync.service:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.petra.json.web.service.client:jar:9.0.1:compile
[INFO] +- com.liferay:com.liferay.petra.mail:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.petra.content:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.petra.log4j:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.petra.io.delta:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.petra.mail.template:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.petra.xml:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.petra.model.adapter:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.petra.encryptor:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.petra.doulos:jar:4.0.2:compile
[INFO] +- com.liferay:com.liferay.configuration.admin.web:jar:2.0.28:compile
[INFO] +- com.liferay:com.liferay.configuration.admin.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.network.utilities.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.pop.notifications:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.dao.orm.custom.sql.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.monitoring:jar:6.0.9:compile
[INFO] +- com.liferay:com.liferay.portal.dao.orm.custom.sql.impl:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.executor:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.weblogic.support:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.inactive.request.handler:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.compound.session.id:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.upgrade.impl:jar:2.0.13:compile
[INFO] +- com.liferay:com.liferay.portal.jmx:jar:5.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.instance.lifecycle.impl:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.spring.extender.impl:jar:1.0.15:compile
[INFO] +- com.liferay:com.liferay.portal.instance.lifecycle.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.upload:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.license.deployer:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.jmx.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.init.servlet.filter:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.custom.jsp.bag.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.output.stream.container.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.upgrade.api:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.output.stream.container:jar:4.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.spring.extender.api:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.messaging:jar:5.0.11:compile
[INFO] +- com.liferay:com.liferay.portal.cluster.multiple:jar:2.0.17:compile
[INFO] +- com.liferay:com.liferay.portal.verify.extender:jar:4.0.4:compile
[INFO] +- com.liferay:com.liferay.layout.admin.web:jar:2.0.60:compile
[INFO] +- com.liferay:com.liferay.layout.set.prototype.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.layout.set.prototype.web:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.layout.page.template.api:jar:1.4.0:compile
[INFO] +- com.liferay:com.liferay.layout.item.selector.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.layout.prototype.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.layout.prototype.impl:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.layout.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.layout.set.prototype.impl:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.layout.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.layout.taglib:jar:3.0.11:compile
[INFO] +- com.liferay:com.liferay.layout.item.selector.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.layout.type.controller.link.to.page:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.layout.type.controller.asset.display:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.layout.type.controller.control.panel:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.layout.type.controller.node:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.layout.type.controller.full.page.application:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.layout.type.controller.content:jar:1.0.9:compile
[INFO] +- com.liferay:com.liferay.layout.page.template.service:jar:1.0.19:compile
[INFO] +- com.liferay:com.liferay.layout.admin.api:jar:1.1.0:compile
[INFO] +- com.liferay:com.liferay.layout.impl:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.quick.note.web:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.map.api:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.map.google.maps:jar:2.0.11:compile
[INFO] +- com.liferay:com.liferay.map.common:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.map.openstreetmap:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.map.taglib:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.xsl.content.web:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.friendly.url.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.friendly.url.service:jar:1.0.18:compile
[INFO] +- com.liferay:com.liferay.upload.web:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.upload.api:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.frontend.taglib.util.freemarker.contributor:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.frontend.taglib.soy:jar:2.1.2:compile
[INFO] +- com.liferay:com.liferay.frontend.taglib.dynamic.section:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.frontend.taglib.util:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.frontend.taglib:jar:3.1.11:compile
[INFO] +- com.liferay:com.liferay.frontend.taglib.chart:jar:1.0.12:compile
[INFO] +- com.liferay:com.liferay.frontend.taglib.clay:jar:1.2.6:compile
[INFO] +- com.liferay:com.liferay.frontend.taglib.form.navigator:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.web.form.web:jar:2.0.9:compile
[INFO] +- com.liferay:com.liferay.site.teams.web:jar:2.0.8:compile
[INFO] +- com.liferay:com.liferay.site.item.selector.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.site.browser.web:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.site.taglib:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.site.memberships.web:jar:2.0.12:compile
[INFO] +- com.liferay:com.liferay.site.teams.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.site.impl:jar:1.0.9:compile
[INFO] +- com.liferay:com.liferay.site.my.sites.web:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.site.service:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.site.item.selector.web:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.site.api:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.site.admin.web:jar:2.0.18:compile
[INFO] +- com.liferay:com.liferay.frontend.js.portlet.extender:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.youtube.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.subscription.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.subscription.service:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.subscription.web:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.organizations.service:jar:1.0.9:compile
[INFO] +- com.liferay:com.liferay.organizations.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.organizations.item.selector.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.organizations.item.selector.web:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.portlet.bridge.soy.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.portlet.bridge.soy.impl:jar:1.0.8:compile
[INFO] +- com.liferay:com.liferay.google.maps.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.html.preview.processor.image:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.html.preview.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.html.preview.service:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.bookmarks.web:jar:2.0.19:compile
[INFO] +- com.liferay:com.liferay.bookmarks.api:jar:3.0.10:compile
[INFO] +- com.liferay:com.liferay.bookmarks.service:jar:2.0.22:compile
[INFO] +- com.liferay:com.liferay.bookmarks.uad:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.nested.portlets.web:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.ratings.page.ratings.web:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.ratings.api:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.ratings.service:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.ratings.analytics:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.security.wedeploy.auth.api:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.security.wedeploy.auth.service:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.security.wedeploy.auth.web:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.roles.admin.api:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.roles.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.roles.item.selector.web:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.roles.item.selector.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.roles.admin.web:jar:2.0.27:compile
[INFO] +- com.liferay:com.liferay.roles.selector.web:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.roles.admin.impl:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.recent.documents.web:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.meris.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.comment.api:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.comment.page.comments.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.comment.web:jar:3.0.11:compile
[INFO] +- com.liferay:com.liferay.comment.analytics:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.comment.taglib:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.comment.editor.configuration:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.comment.ratings.definition:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.comment.sanitizer:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.microsoft.translator:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.asset.api:jar:1.1.1:compile
[INFO] +- com.liferay:com.liferay.asset.tags.navigation.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.asset.test.util:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.asset.tags.selector.web:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.asset.tags.service:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.asset.display.impl:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.asset.entry.rel.api:jar:1.1.0:compile
[INFO] +- com.liferay:com.liferay.asset.category.property.service:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.asset.tag.stats.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.asset.taglib:jar:3.0.13:compile
[INFO] +- com.liferay:com.liferay.asset.display.api:jar:1.2.0:compile
[INFO] +- com.liferay:com.liferay.asset.browser.web:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.asset.display.web:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.asset.display.page.api:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.asset.tag.stats.service:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.asset.publisher.web:jar:2.0.39:compile
[INFO] +- com.liferay:com.liferay.asset.categories.service:jar:2.0.9:compile
[INFO] +- com.liferay:com.liferay.asset.categories.navigation.web:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.asset.display.page.item.selector.web:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.asset.tags.admin.web:jar:2.0.13:compile
[INFO] +- com.liferay:com.liferay.asset.display.page.item.selector.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.asset.tags.compiler.web:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.asset.display.page.service:jar:1.0.11:compile
[INFO] +- com.liferay:com.liferay.asset.tags.navigation.web:jar:4.0.6:compile
[INFO] +- com.liferay:com.liferay.asset.publisher.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.asset.entry.rel.service:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.asset.tags.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.asset.categories.admin.web:jar:2.0.13:compile
[INFO] +- com.liferay:com.liferay.asset.web:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.asset.category.property.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.asset.entry.query.processor.custom.user.attributes:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.asset.categories.navigation.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.asset.categories.selector.web:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.asset.service:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.asset.publisher.layout.prototype:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.asset.link.service:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.staging.api:jar:3.1.0:compile
[INFO] +- com.liferay:com.liferay.staging.security:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.staging.processes.web:jar:2.0.19:compile
[INFO] +- com.liferay:com.liferay.staging.configuration.web:jar:2.0.12:compile
[INFO] +- com.liferay:com.liferay.staging.bar.web:jar:2.0.16:compile
[INFO] +- com.liferay:com.liferay.staging.lang:jar:3.0.16:compile
[INFO] +- com.liferay:com.liferay.staging.portlet.data.handler:jar:4.0.0:compile
[INFO] +- com.liferay:com.liferay.staging.impl:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.staging.taglib:jar:4.1.3:compile
[INFO] +- com.liferay:com.liferay.push.notifications.service:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.push.notifications.api:jar:2.1.2:compile
[INFO] +- com.liferay:com.liferay.push.notifications.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.push.notifications.sender.sms:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.push.notifications.sender.android:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.push.notifications.sender.microsoft:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.push.notifications.sender.firebase:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.push.notifications.sender.apple:jar:2.0.8:compile
[INFO] +- com.liferay:com.liferay.frontend.editor.lang:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.frontend.editor.alloyeditor.web:jar:2.0.18:compile
[INFO] +- com.liferay:com.liferay.frontend.editor.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.frontend.editor.simple.web:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.frontend.editor.taglib:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.frontend.editor.tinymce.web:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.frontend.editor.ckeditor.web:jar:2.0.18:compile
[INFO] +- com.liferay:com.liferay.knowledge.base.item.selector.web:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.knowledge.base.service:jar:2.0.22:compile
[INFO] +- com.liferay:com.liferay.knowledge.base.item.selector.api:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.knowledge.base.markdown.converter.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.knowledge.base.editor.configuration:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.knowledge.base.api:jar:5.0.11:compile
[INFO] +- com.liferay:com.liferay.knowledge.base.web:jar:2.0.31:compile
[INFO] +- com.liferay:com.liferay.knowledge.base.markdown.converter.impl:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.external.reference.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.external.reference.service:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.my.subscriptions.web:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.debug.spring.extender:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.debug.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.debug.impl:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.debug.declarative.service:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.text.localizer.address.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.text.localizer.taglib:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.template.velocity:jar:3.0.14:compile
[INFO] +- com.liferay:com.liferay.portal.template.soy.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.template.freemarker:jar:4.0.15:compile
[INFO] +- com.liferay:com.liferay.portal.template.xsl:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.template.soy.impl:jar:1.0.12:compile
[INFO] +- com.liferay:com.liferay.portal.template.soy.context.contributor:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portlet.display.template.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.portlet.display.template.web:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.portlet.display.template.impl:jar:1.0.9:compile
[INFO] +- com.liferay:com.liferay.application.list.user.personal.site.permissions:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.application.list.taglib:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.application.list.api:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.application.list.my.account.permissions:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.openid.api:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.facebook.connect.impl:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.token.impl:jar:2.0.8:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.google.impl:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.openid.connect.api:jar:2.1.0:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.facebook.connect.api:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.ntlm.impl:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.ntlm.api:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.opensso.impl:jar:1.0.8:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.openid.impl:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.cas.impl:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.opensso.api:jar:2.1.1:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.google.api:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.openid.connect.impl:jar:1.0.14:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.token.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.security.sso.cas.api:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.reports.engine.api:jar:4.0.1:compile
[INFO] +- com.liferay:com.liferay.gogo.shell.web:jar:2.0.17:compile
[INFO] +- com.liferay:com.liferay.server.admin.web:jar:2.0.17:compile
[INFO] +- com.liferay:com.liferay.translator.web:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.user.associated.data.web:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.user.associated.data.api:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.user.associated.data.test.util:jar:4.0.0:compile
[INFO] +- com.liferay:com.liferay.hello.world.web:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.alloy.mvc:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.bean.portlet.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.bean.portlet.cdi.extension:jar:1.0.8:compile
[INFO] +- com.liferay:com.liferay.expando.web:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.expando.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.expando.exportimport:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.expando.taglib:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.blogs.service:jar:2.0.21:compile
[INFO] +- com.liferay:com.liferay.blogs.web:jar:3.0.34:compile
[INFO] +- com.liferay:com.liferay.blogs.item.selector.web:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.blogs.test.util:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.blogs.recent.bloggers.web:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.blogs.api:jar:4.0.7:compile
[INFO] +- com.liferay:com.liferay.blogs.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.blogs.recent.bloggers.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.blogs.layout.prototype:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.blogs.item.selector.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.blogs.reading.time:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.blogs.editor.configuration:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.invitation.invite.members.service:jar:4.0.7:compile
[INFO] +- com.liferay:com.liferay.invitation.invite.members.web:jar:2.0.9:compile
[INFO] +- com.liferay:com.liferay.invitation.invite.members.api:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.frontend.theme.unstyled:jar:3.0.16:compile
[INFO] +- com.liferay:com.liferay.frontend.theme.styled:jar:3.0.12:compile
[INFO] +- com.liferay:com.liferay.frontend.theme.favicon.servlet:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.frontend.theme.contributor.extender:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.frontend.compatibility.ie:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.changeset.api:jar:1.2.2:compile
[INFO] +- com.liferay:com.liferay.changeset.service:jar:1.0.8:compile
[INFO] +- com.liferay:com.liferay.currency.converter.web:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.currency.converter.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.loan.calculator.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.screens.service:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.screens.api:jar:4.0.0:compile
[INFO] +- com.liferay:com.liferay.fragment.taglib:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.fragment.service:jar:1.0.18:compile
[INFO] +- com.liferay:com.liferay.fragment.item.selector.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.fragment.impl:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.fragment.web:jar:1.0.36:compile
[INFO] +- com.liferay:com.liferay.fragment.entry.processor.portlet:jar:1.0.8:compile
[INFO] +- com.liferay:com.liferay.fragment.entry.processor.editable:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.fragment.entry.processor.nullable:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.fragment.api:jar:1.1.4:compile
[INFO] +- com.liferay:com.liferay.fragment.item.selector.web:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.fragment.display.web:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.exportimport.changeset.service:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.exportimport.changeset.web:jar:1.0.16:compile
[INFO] +- com.liferay:com.liferay.exportimport.web:jar:2.0.29:compile
[INFO] +- com.liferay:com.liferay.exportimport.changeset.taglib:jar:1.0.12:compile
[INFO] +- com.liferay:com.liferay.exportimport.resources.importer:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.exportimport.service:jar:5.0.44:compile
[INFO] +- com.liferay:com.liferay.exportimport.changeset.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.exportimport.test.util:jar:1.2.8:compile
[INFO] +- com.liferay:com.liferay.exportimport.api:jar:3.0.9:compile
[INFO] +- com.liferay:com.liferay.item.selector.upload.web:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.item.selector.criteria.api:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.item.selector.web:jar:4.0.12:compile
[INFO] +- com.liferay:com.liferay.item.selector.taglib:jar:2.0.10:compile
[INFO] +- com.liferay:com.liferay.item.selector.editor.configuration:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.item.selector.api:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.item.selector.url.web:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.item.selector.impl:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.item.selector.criteria.impl:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.sync.service:jar:2.0.19:compile
[INFO] +- com.liferay:com.liferay.sync.api:jar:4.0.5:compile
[INFO] +- com.liferay:com.liferay.sync.web:jar:2.0.11:compile
[INFO] +- com.liferay:com.liferay.sync.security:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.frontend.theme.westeros.bank.site.initializer:jar:1.0.9:compile
[INFO] +- com.liferay:com.liferay.message.boards.test.util:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.message.boards.comment:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.message.boards.web:jar:2.0.33:compile
[INFO] +- com.liferay:com.liferay.message.boards.parser.bbcode:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.message.boards.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.message.boards.editor.configuration:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.message.boards.api:jar:4.2.3:compile
[INFO] +- com.liferay:com.liferay.message.boards.service:jar:2.0.27:compile
[INFO] +- com.liferay:com.liferay.message.boards.layout.set.prototype:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.mobile.device.detection.fiftyonedegrees.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.mobile.device.detection.fiftyonedegrees:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.amazon.rankings.web:jar:2.0.9:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.io:jar:3.0.11:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.form.field.type:jar:3.0.19:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.form.taglib:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.form.renderer:jar:3.0.26:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.lang:jar:3.0.10:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.api:jar:4.8.0:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.form.values.query:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.validator:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.test.util:jar:3.2.1:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.web:jar:2.0.33:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.data.provider.impl:jar:2.0.11:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.expression:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.data.provider.web:jar:2.0.14:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.form.values.factory:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.form.builder:jar:1.0.36:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.data.provider.instance:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.service:jar:3.0.46:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.form.analytics:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.form.evaluator.impl:jar:1.0.8:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.form.web:jar:1.0.50:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.mapping.taglib:jar:3.3.0:compile
[INFO] +- com.liferay:com.liferay.users.admin.item.selector.web:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.users.admin.test.util:jar:1.1.0:compile
[INFO] +- com.liferay:com.liferay.users.admin.web:jar:3.0.36:compile
[INFO] +- com.liferay:com.liferay.users.admin.item.selector.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.users.admin.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.users.admin.api:jar:3.0.16:compile
[INFO] +- com.liferay:com.liferay.users.admin.impl:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.captcha.taglib:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.captcha.impl:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.captcha.api:jar:2.0.9:compile
[INFO] +- com.liferay:com.liferay.flags.service:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.flags.api:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.flags.taglib:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.flags.web:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.journal.taglib:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.journal.terms.of.use:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.journal.item.selector.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.journal.editor.configuration:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.journal.ratings.definition:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.journal.content.web:jar:3.0.21:compile
[INFO] +- com.liferay:com.liferay.journal.api:jar:3.5.0:compile
[INFO] +- com.liferay:com.liferay.journal.item.selector.api:jar:2.1.0:compile
[INFO] +- com.liferay:com.liferay.journal.web:jar:2.0.40:compile
[INFO] +- com.liferay:com.liferay.journal.content.asset.addon.entry.conversions:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.journal.content.asset.addon.entry.related.assets:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.journal.content.asset.addon.entry.print:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.journal.content.asset.addon.entry.comments:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.journal.content.asset.addon.entry.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.journal.content.asset.addon.entry.locales:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.journal.content.asset.addon.entry.ratings:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.journal.test.util:jar:2.1.2:compile
[INFO] +- com.liferay:com.liferay.journal.service:jar:4.0.45:compile
[INFO] +- com.liferay:com.liferay.journal.lang:jar:3.0.18:compile
[INFO] +- com.liferay:com.liferay.portal.store.cmis:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.store.safe.file.name.wrapper:jar:2.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.store.db:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.store.file.system:jar:3.0.9:compile
[INFO] +- com.liferay:com.liferay.portal.store.ignore.duplicates.wrapper:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.store.jcr:jar:3.0.11:compile
[INFO] +- com.liferay:com.liferay.portal.store.s3:jar:3.0.24:compile
[INFO] +- com.liferay:com.liferay.weather.web:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.frontend.theme.porygon.site.initializer:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.announcements.uad:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.announcements.web:jar:3.0.16:compile
[INFO] +- com.liferay:com.liferay.announcements.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.announcements.editor.configuration:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.user.groups.admin.impl:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.user.groups.admin.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.user.groups.admin.api:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.user.groups.admin.item.selector.web:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.user.groups.admin.web:jar:2.0.12:compile
[INFO] +- com.liferay:com.liferay.user.groups.admin.item.selector.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.model.relationship.document.library.impl:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.model.relationship.dynamic.data.mapping.impl:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.web.proxy.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.lists.service:jar:2.0.20:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.lists.api:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.dynamic.data.lists.web:jar:3.0.23:compile
[INFO] +- com.liferay:com.liferay.portal.cache.test.util:jar:2.0.11:compile
[INFO] +- com.liferay:com.liferay.portal.cache.ehcache.provider:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.cache.ehcache.spi:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.cache.ehcache.impl:jar:1.0.11:compile
[INFO] +- com.liferay:com.liferay.portal.cache.api:jar:1.1.1:compile
[INFO] +- com.liferay:com.liferay.portal.cache.multiple:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.portal.cache.impl:jar:1.0.13:compile
[INFO] +- com.liferay:com.liferay.social.activities.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.social.bookmark.linkedin:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.social.activities.taglib:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.social.bookmark.plusone:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.social.bookmark.facebook:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.social.bookmarks.analytics:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.social.activity.api:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.social.bookmarks.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.social.activities.web:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.social.user.statistics.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.social.activity.test.util:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.social.bookmark.twitter:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.social.bookmarks.taglib:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.mobile.device.recognition.impl:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.settings.authentication.google.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.settings.authentication.cas.web:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.settings.authentication.facebook.connect.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.settings.authentication.ntlm.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.settings.authentication.opensso.web:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.settings.authentication.ldap.web:jar:2.0.11:compile
[INFO] +- com.liferay:com.liferay.portal.settings.api:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.settings.authentication.openid.connect.web:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.settings.authentication.openid.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.settings.web:jar:2.0.15:compile
[INFO] +- com.liferay:com.liferay.portal.settings.lang:jar:2.0.11:compile
[INFO] +- com.liferay:com.liferay.site.navigation.site.map.web:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.site.navigation.directory.web:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.site.navigation.admin.web:jar:1.0.21:compile
[INFO] +- com.liferay:com.liferay.site.navigation.admin.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.site.navigation.menu.item.layout:jar:1.0.13:compile
[INFO] +- com.liferay:com.liferay.site.navigation.menu.web:jar:3.0.19:compile
[INFO] +- com.liferay:com.liferay.site.navigation.menu.item.url:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.site.navigation.api:jar:2.3.0:compile
[INFO] +- com.liferay:com.liferay.site.navigation.breadcrumb.web:jar:4.0.7:compile
[INFO] +- com.liferay:com.liferay.site.navigation.menu.item.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.site.navigation.lang:jar:1.0.15:compile
[INFO] +- com.liferay:com.liferay.site.navigation.item.selector.web:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.site.navigation.language.web:jar:4.0.5:compile
[INFO] +- com.liferay:com.liferay.site.navigation.language.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.site.navigation.menu.item.node:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.site.navigation.item.selector.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.site.navigation.service:jar:1.0.20:compile
[INFO] +- com.liferay:com.liferay.site.navigation.taglib:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.frontend.js.lodash.web:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.frontend.js.polyfill.babel.web:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.frontend.js.loader.modules.extender.api:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.frontend.js.top.head.extender:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.frontend.js.minifier:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.frontend.js.aui.web:jar:2.0.32:compile
[INFO] +- com.liferay:com.liferay.frontend.js.bundle.config.extender:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.frontend.js.loader.modules.extender:jar:3.0.17:compile
[INFO] +- com.liferay:com.liferay.frontend.js.web:jar:2.0.31:compile
[INFO] +- com.liferay:com.liferay.frontend.js.spa.web:jar:2.0.15:compile
[INFO] +- com.liferay:com.liferay.frontend.js.metal.web:jar:2.0.5:compile
[INFO] +- com.liferay:com.liferay.frontend.js.node.shims:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.mentions.web:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.mentions.api:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.mentions.service:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.scheduler.quartz:jar:4.0.8:compile
[INFO] +- com.liferay:com.liferay.portal.scheduler.multiple:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.portal.scheduler:jar:5.0.9:compile
[INFO] +- com.liferay:com.liferay.password.generator.web:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.xstream.configurator.api:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.calendar.api:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.calendar.web:jar:2.0.28:compile
[INFO] +- com.liferay:com.liferay.calendar.service:jar:3.0.20:compile
[INFO] +- com.liferay:com.liferay.reading.time.web:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.reading.time.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.reading.time.taglib:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.reading.time.editor.plugin:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.reading.time.service:jar:1.0.8:compile
[INFO] +- com.liferay:com.liferay.portal.scripting.beanshell:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.persistence.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.persistence.impl:jar:1.0.9:compile
[INFO] +- com.liferay:com.liferay.portal.configuration.metatype.api:jar:1.1.6:compile
[INFO] +- com.liferay:com.liferay.portal.lpkg.deployer.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.lpkg.deployer.impl:jar:1.0.19:compile
[INFO] +- com.liferay:com.liferay.portal.lpkg.deployer.test.util:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.osgi.util:jar:4.1.1:compile
[INFO] +- com.liferay:com.liferay.osgi.felix.file.install.configuration.cleaner:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.classloader.tracker:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.log4j.extender:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.social.activity.extender:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.profile.impl:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.profile.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.bundle.blacklist.impl:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.portal.bundle.blacklist.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.portlet.tracker:jar:3.0.11:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.servlet.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.wab.spring.bridge.api:jar:1.0.8:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.servlet.context.helper.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.wab.reference.support:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.servlet.jsp.compiler:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.wab.extender:jar:3.0.21:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.wab.generator.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.servlet.context.helper.impl:jar:1.0.9:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.jasper.plugins.taglib:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.osgi.web.wab.generator.impl:jar:1.0.23:compile
[INFO] +- com.liferay:com.liferay.portal.component.blacklist.impl:jar:2.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.component.blacklist.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.target.platform.indexer.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.target.platform.indexer.impl:jar:1.0.13:compile
[INFO] +- com.liferay:com.liferay.hello.soy.navigation.web:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.hello.soy.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.scripting.executor:jar:4.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.scripting.impl:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.portal.scripting.groovy.context.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.scripting.api:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.scripting.groovy:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.login.authentication.google.web:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.login.authentication.facebook.connect.web:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.login.authentication.openid.connect.web:jar:1.0.11:compile
[INFO] +- com.liferay:com.liferay.login.web:jar:3.0.18:compile
[INFO] +- com.liferay:com.liferay.login.authentication.openid.web:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.phone.apio.impl:jar:1.0.10:compile
[INFO] +- com.liferay:com.liferay.phone.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.role.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.role.apio.impl:jar:1.0.10:compile
[INFO] +- com.liferay:com.liferay.structure.apio.api:jar:1.3.1:compile
[INFO] +- com.liferay:com.liferay.structure.apio.impl:jar:1.0.17:compile
[INFO] +- com.liferay:com.liferay.forms.apio.api:jar:1.1.4:compile
[INFO] +- com.liferay:com.liferay.forms.apio.impl:jar:1.0.23:compile
[INFO] +- com.liferay:com.liferay.portal.apio.test.util:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.apio.api:jar:1.2.1:compile
[INFO] +- com.liferay:com.liferay.portal.apio.impl:jar:1.0.13:compile
[INFO] +- com.liferay:com.liferay.layout.apio.impl:jar:1.0.8:compile
[INFO] +- com.liferay:com.liferay.layout.apio.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.organization.apio.impl:jar:1.0.16:compile
[INFO] +- com.liferay:com.liferay.organization.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.site.apio.impl:jar:1.0.15:compile
[INFO] +- com.liferay:com.liferay.site.apio.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.content.space.apio.impl:jar:1.0.14:compile
[INFO] +- com.liferay:com.liferay.content.space.apio.api:jar:1.1.2:compile
[INFO] +- com.liferay:com.liferay.aggregate.rating.apio.impl:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.aggregate.rating.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.vocabulary.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.vocabulary.apio.impl:jar:1.0.15:compile
[INFO] +- com.liferay:com.liferay.media.object.apio.impl:jar:1.0.17:compile
[INFO] +- com.liferay:com.liferay.media.object.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.comment.apio.api:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.comment.apio.impl:jar:1.0.12:compile
[INFO] +- com.liferay:com.liferay.category.apio.impl:jar:1.0.16:compile
[INFO] +- com.liferay:com.liferay.category.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.person.apio.api:jar:1.1.3:compile
[INFO] +- com.liferay:com.liferay.person.apio.impl:jar:1.0.16:compile
[INFO] +- com.liferay:com.liferay.address.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.address.apio.impl:jar:1.0.12:compile
[INFO] +- com.liferay:com.liferay.structured.content.apio.impl:jar:1.0.39:compile
[INFO] +- com.liferay:com.liferay.structured.content.apio.api:jar:1.8.1:compile
[INFO] +- com.liferay:com.liferay.keyword.apio.impl:jar:1.0.11:compile
[INFO] +- com.liferay:com.liferay.keyword.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.blog.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.blog.apio.impl:jar:1.0.21:compile
[INFO] +- com.liferay:com.liferay.web.url.apio.impl:jar:1.0.11:compile
[INFO] +- com.liferay:com.liferay.web.url.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.workflow.apio.api:jar:1.2.2:compile
[INFO] +- com.liferay:com.liferay.workflow.apio.impl:jar:1.0.21:compile
[INFO] +- com.liferay:com.liferay.email.apio.impl:jar:1.0.11:compile
[INFO] +- com.liferay:com.liferay.email.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.folder.apio.impl:jar:1.0.10:compile
[INFO] +- com.liferay:com.liferay.folder.apio.api:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.product.navigation.control.panel:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.product.navigation.simulation.web:jar:4.0.6:compile
[INFO] +- com.liferay:com.liferay.product.navigation.product.menu.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.product.navigation.site.administration:jar:3.0.9:compile
[INFO] +- com.liferay:com.liferay.product.navigation.user.personal.bar.web:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.product.navigation.control.menu.api:jar:4.0.1:compile
[INFO] +- com.liferay:com.liferay.product.navigation.user:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.product.navigation.product.menu.web:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.product.navigation.simulation.device:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.product.navigation.simulation.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.product.navigation.control.menu.theme.contributor:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.product.navigation.taglib:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.product.navigation.product.menu.theme.contributor:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.product.navigation.control.menu.web:jar:3.0.12:compile
[INFO] +- com.liferay:com.liferay.product.navigation.simulation.theme.contributor:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.product.navigation.control.menu.impl:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.security.antisamy:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.portal.security.permission.api:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.security.service.access.policy.web:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.portal.security.service.access.policy.api:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.security.ldap.impl:jar:1.0.26:compile
[INFO] +- com.liferay:com.liferay.portal.security.service.access.policy.service:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.security.ldap.api:jar:1.2.5:compile
[INFO] +- com.liferay:com.liferay.portal.security.permission.impl:jar:1.0.7:compile
[INFO] +- com.liferay:com.liferay.portal.security.auth.verifier:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.security.service.access.quota.api:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.security.exportimport.api:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.portal.security.auto.login:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.portal.validation.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.microblogs.api:jar:3.0.4:compile
[INFO] +- com.liferay:com.liferay.microblogs.web:jar:3.0.11:compile
[INFO] +- com.liferay:com.liferay.microblogs.service:jar:3.0.9:compile
[INFO] +- com.liferay:com.liferay.portal.odata.api:jar:1.8.2:compile
[INFO] +- com.liferay:com.liferay.portal.odata.impl:jar:1.0.15:compile
[INFO] +- com.liferay:com.liferay.notifications.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.notifications.web:jar:2.0.9:compile
[INFO] +- com.liferay:com.liferay.flash.web:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.trash.test.util:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.trash.web:jar:2.0.12:compile
[INFO] +- com.liferay:com.liferay.trash.service:jar:2.0.10:compile
[INFO] +- com.liferay:com.liferay.trash.api:jar:1.0.5:compile
[INFO] +- com.liferay:com.liferay.trash.taglib:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.scripting.ruby:jar:3.0.3:compile
[INFO] +- com.liferay:com.liferay.portal.language.servlet.filter:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.portal.language.extender:jar:3.0.10:compile
[INFO] +- com.liferay:com.liferay.imageio.plugins:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.portal.background.task.service:jar:4.0.15:compile
[INFO] +- com.liferay:com.liferay.portal.background.task.api:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.portal.background.task.web:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.frontend.theme.fjord.site.initializer:jar:1.0.6:compile
[INFO] +- com.liferay:com.liferay.hello.velocity.web:jar:3.0.2:compile
[INFO] +- com.liferay:com.liferay.wiki.engine.html:jar:3.0.0:compile
[INFO] +- com.liferay:com.liferay.wiki.uad:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.wiki.editor.link.browse.web:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.wiki.layout.prototype:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.wiki.engine.lang:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.wiki.api:jar:3.0.6:compile
[INFO] +- com.liferay:com.liferay.wiki.engine.text:jar:3.0.1:compile
[INFO] +- com.liferay:com.liferay.wiki.web:jar:4.0.32:compile
[INFO] +- com.liferay:com.liferay.wiki.engine.creole:jar:3.0.8:compile
[INFO] +- com.liferay:com.liferay.wiki.engine.input.editor.common:jar:4.0.4:compile
[INFO] +- com.liferay:com.liferay.wiki.navigation.web:jar:3.0.5:compile
[INFO] +- com.liferay:com.liferay.wiki.editor.configuration:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.wiki.service:jar:2.0.21:compile
[INFO] +- com.liferay:com.liferay.plugins.admin.web:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.analytics.api:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.analytics.data.binding.impl:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.scope.impl:jar:1.0.29:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.shortcut:jar:1.0.4:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.scope.liferay.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.scope.spi:jar:1.0.2:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.rest.spi:jar:1.0.1:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.api:jar:1.2.1:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.rest:jar:1.0.31:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.jsonws:jar:1.0.20:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.scope.api:jar:1.0.3:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.web:jar:1.0.33:compile
[INFO] +- com.liferay:com.liferay.oauth2.provider.service:jar:1.0.15:compile
[INFO] +- com.liferay:com.liferay.osgi.felix.util:jar:2.0.0:compile
[INFO] +- com.liferay:com.liferay.jaxws.osgi.bridge:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.registry.impl:jar:2.0.16:compile
[INFO] +- com.liferay:com.liferay.petra.concurrent:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.petra.reflect:jar:2.1.3:compile
[INFO] +- com.liferay:com.liferay.petra.lang:jar:2.0.7:compile
[INFO] +- com.liferay:com.liferay.petra.nio:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.petra.string:jar:2.1.3:compile
[INFO] +- com.liferay:com.liferay.petra.io:jar:2.0.6:compile
[INFO] +- com.liferay:com.liferay.petra.memory:jar:2.0.2:compile
[INFO] +- com.liferay:com.liferay.petra.executor:jar:2.0.1:compile
[INFO] +- com.liferay:com.liferay.petra.function:jar:2.1.1:compile
[INFO] +- com.liferay:com.liferay.petra.process:jar:2.0.14:compile
[INFO] +- com.liferay:com.liferay.osgi.service.tracker.collections:jar:3.0.7:compile
[INFO] +- com.liferay:com.liferay.registry.api:jar:2.1.3:compile
[INFO] +- com.liferay:com.liferay.portal.equinox.log.bridge:jar:2.0.8:compile
[INFO] +- com.liferay.portal:com.liferay.portal.kernel:jar:3.46.1:compile
[INFO] +- com.liferay.portal:com.liferay.portal.impl:jar:3.26.3:compile
[INFO] +- com.liferay.portal:com.liferay.portal.test:jar:5.3.0:compile
[INFO] +- com.liferay.portal:com.liferay.portal.test.integration:jar:5.1.6:compile
[INFO] +- com.liferay.portal:com.liferay.support.tomcat:jar:2.1.0:compile
[INFO] +- com.liferay.portal:com.liferay.util.bridges:jar:5.0.0:compile
[INFO] +- com.liferay.portal:com.liferay.util.java:jar:3.0.16:compile
[INFO] +- com.liferay.portal:com.liferay.util.slf4j:jar:3.0.1:compile
[INFO] +- com.liferay.portal:com.liferay.util.taglib:jar:3.3.12:compile
[INFO] +- com.liferay:com.java2html:jar:1.5:compile
[INFO] +- io.appium:java-client:jar:1.6.2:compile
[INFO] |  +- org.seleniumhq.selenium:selenium-java:jar:2.42.2:compile
[INFO] |  |  +- org.seleniumhq.selenium:selenium-chrome-driver:jar:2.42.2:compile
[INFO] |  |  +- org.seleniumhq.selenium:selenium-htmlunit-driver:jar:2.42.2:compile
[INFO] |  |  |  \- net.sourceforge.htmlunit:htmlunit:jar:2.14:compile
[INFO] |  |  |     +- org.apache.commons:commons-lang3:jar:3.2.1:compile
[INFO] |  |  |     +- net.sourceforge.htmlunit:htmlunit-core-js:jar:2.14:compile
[INFO] |  |  |     +- net.sourceforge.cssparser:cssparser:jar:0.9.13:compile
[INFO] |  |  |     |  \- org.w3c.css:sac:jar:1.3:compile
[INFO] |  |  |     \- org.eclipse.jetty:jetty-websocket:jar:8.1.14.v20131031:compile
[INFO] |  |  +- org.seleniumhq.selenium:selenium-ie-driver:jar:2.42.2:compile
[INFO] |  |  |  \- net.java.dev.jna:platform:jar:3.4.0:compile
[INFO] |  |  +- org.seleniumhq.selenium:selenium-safari-driver:jar:2.42.2:compile
[INFO] |  |  +- org.seleniumhq.selenium:selenium-support:jar:2.42.2:compile
[INFO] |  |  |  \- org.seleniumhq.selenium:selenium-api:jar:2.42.2:compile
[INFO] |  |  \- org.webbitserver:webbit:jar:0.4.14:compile
[INFO] |  |     \- io.netty:netty:jar:3.5.2.Final:compile
[INFO] |  +- com.google.guava:guava:jar:17.0:compile
[INFO] |  \- cglib:cglib:jar:3.1:compile
[INFO] +- mysql:mysql-connector-java:jar:5.1.23:compile
[INFO] +- velocity-tools:velocity-tools:jar:1.4:compile
[INFO] +- org.mariadb.jdbc:mariadb-java-client:jar:1.1.9:compile
[INFO] |  \- net.java.dev.jna:jna:jar:platform:3.3.0:compile
[INFO] +- com.sun.mail:smtp:jar:1.5.4:compile
[INFO] +- com.thoughtworks.qdox:qdox:jar:1.12.1:compile
[INFO] +- javaee:sdk-addon-api:jar:0.2:compile
[INFO] +- javax.mail:mail:jar:1.4:compile
[INFO] +- org.hsqldb:hsqldb:jar:2.3.3:compile
[INFO] +- org.powermock:powermock-core:jar:1.6.1:compile
[INFO] +- javax.annotation:jsr250-api:jar:1.0:compile
[INFO] +- org.objenesis:objenesis:jar:2.1:compile
[INFO] +- org.apache.tomcat:tomcat-api:jar:9.0.10:compile
[INFO] |  \- org.apache.tomcat:tomcat-servlet-api:jar:9.0.10:compile
[INFO] +- org.apache.tomcat:tomcat-coyote:jar:9.0.10:compile
[INFO] |  \- org.apache.tomcat:tomcat-jni:jar:9.0.10:compile
[INFO] +- javax.servlet.jsp:jsp-api:jar:2.1:compile
[INFO] +- com.liferay:com.liferay.jenkins.results.parser:jar:1.0.386:compile
[INFO] |  +- com.amazonaws:aws-java-sdk-core:jar:1.11.220:compile
[INFO] |  |  +- software.amazon.ion:ion-java:jar:1.0.2:compile
[INFO] |  |  +- com.fasterxml.jackson.dataformat:jackson-dataformat-cbor:jar:2.6.7:compile
[INFO] |  |  \- joda-time:joda-time:jar:2.8.1:compile
[INFO] |  +- com.amazonaws:aws-java-sdk-ec2:jar:1.11.220:compile
[INFO] |  |  \- com.amazonaws:jmespath-java:jar:1.11.220:compile
[INFO] |  +- com.amazonaws:aws-java-sdk-rds:jar:1.11.220:compile
[INFO] |  \- org.json:json:jar:20140107:compile
[INFO] +- org.apache.ant:ant-apache-bsf:jar:1.8.2:compile
[INFO] +- org.mockito:mockito-all:jar:1.9.5:compile
[INFO] +- org.skyscreamer:jsonassert:jar:1.2.3:compile
[INFO] +- javax.transaction:jta:jar:1.1:compile
[INFO] +- org.hamcrest:hamcrest-core:jar:1.3:compile
[INFO] +- org.slf4j:slf4j-simple:jar:1.7.10:compile
[INFO] +- biz.aQute.bnd:biz.aQute.bnd:jar:3.5.0:compile
[INFO] +- javax.websocket:javax.websocket-api:jar:1.1:compile
[INFO] +- javax.jms:jms:jar:1.1:compile
[INFO] +- org.jacoco:org.jacoco.ant:jar:0.7.9:compile
[INFO] +- javax.activation:activation:jar:1.1:compile
[INFO] +- org.jacoco:org.jacoco.core:jar:0.7.9:compile
[INFO] +- com.google.code.gson:gson:jar:2.2.4:compile
[INFO] +- org.jacoco:org.jacoco.report:jar:0.7.9:compile
[INFO] +- com.liferay:javax.naming.jndi:jar:1.2.1:compile
[INFO] +- com.jcraft:jsch:jar:0.1.51:compile
[INFO] +- saxpath:saxpath:jar:1.0-FCS:compile
[INFO] +- com.google.errorprone:error_prone_ant:jar:1.0.8:compile
[INFO] +- com.googlecode.jarjar:jarjar:jar:1.3:compile
[INFO] +- com.beetstra.jutf7:jutf7:jar:1.0.0:compile
[INFO] +- org.powermock:powermock-module-junit4-common:jar:1.6.1:compile
[INFO] +- org.eclipse.jetty:jetty-server:jar:8.1.10.v20130312:compile
[INFO] |  +- org.eclipse.jetty.orbit:javax.servlet:jar:3.0.0.v201112011016:compile
[INFO] |  +- org.eclipse.jetty:jetty-continuation:jar:8.1.10.v20130312:compile
[INFO] |  \- org.eclipse.jetty:jetty-http:jar:8.1.10.v20130312:compile
[INFO] |     \- org.eclipse.jetty:jetty-io:jar:8.1.10.v20130312:compile
[INFO] +- org.springframework:spring-test:jar:4.1.9.RELEASE:compile
[INFO] +- com.liferay:com.dumbster.smtp:jar:02856255a6cc7f:compile
[INFO] +- org.eclipse.persistence:javax.persistence:jar:2.1.1:compile
[INFO] +- net.sf:jargs:jar:1.0:compile
[INFO] +- org.powermock:powermock-api-support:jar:1.6.1:compile
[INFO] +- net.sf.dtddoc:DTDDoc:jar:1.1.0:compile
[INFO] |  +- ant:ant:jar:1.6.5:compile
[INFO] |  +- net.sf.dtddoc:dtdparser:jar:1.20-dtddoc:compile
[INFO] |  \- regexp:regexp:jar:1.2:compile
[INFO] +- taglibrarydoc:tlddoc:jar:1.3:compile
[INFO] +- org.powermock:powermock-reflect:jar:1.6.1:compile
[INFO] +- org.hamcrest:hamcrest-library:jar:1.3:compile
[INFO] +- net.open-esb.core:jbi_rt:jar:2.4.3:compile
[INFO] |  +- net.open-esb.core:base:jar:2.4.3:compile
[INFO] |  |  \- net.open-esb.core:jbi:jar:2.4.3:compile
[INFO] |  |     +- net.open-esb.core:jbi-api:jar:2.4.3:compile
[INFO] |  |     |  \- javax.transaction:transaction-api:jar:1.1:compile
[INFO] |  |     \- net.open-esb.core:jbi-spi:jar:2.4.3:compile
[INFO] |  +- net.open-esb.core:esb-util:jar:2.4.3:compile
[INFO] |  |  \- glassfish:appserv-ext:jar:9.1:compile
[INFO] |  +- net.open-esb.core:framework-core:jar:2.4.3:compile
[INFO] |  +- net.open-esb.core:manage:jar:2.4.3:compile
[INFO] |  |  \- org.apache.ant:ant-nodeps:jar:1.8.1:compile
[INFO] |  +- net.open-esb.core:nmr:jar:2.4.3:compile
[INFO] |  |  \- net.open-esb.core:tracking:jar:2.4.3:compile
[INFO] |  +- net.open-esb.core:jbi-admin-common:jar:2.4.3:compile
[INFO] |  +- net.open-esb.core:ui:jar:2.4.3:compile
[INFO] |  +- net.open-esb.core:wsdl2:jar:2.4.3:compile
[INFO] |  |  \- net.open-esb.core:wsdl:jar:2.4.3:compile
[INFO] |  |     \- xmlbeans:xbean:jar:2.2.0:compile
[INFO] |  \- net.open-esb.core:esb-manage:jar:2.4.3:compile
[INFO] +- org.apache.tomcat:tomcat-jasper:jar:9.0.10:compile
[INFO] |  +- org.apache.tomcat:tomcat-jsp-api:jar:9.0.10:compile
[INFO] |  +- org.apache.tomcat:tomcat-el-api:jar:9.0.10:compile
[INFO] |  +- org.eclipse.jdt:ecj:jar:3.13.102:compile
[INFO] |  +- org.apache.tomcat:tomcat-jasper-el:jar:9.0.10:compile
[INFO] |  \- org.apache.tomcat:tomcat-util-scan:jar:9.0.10:compile
[INFO] +- com.liferay:com.wutka.dtd:jar:1.20:compile
[INFO] +- jalopy:jalopy:jar:1.5rc3:compile
[INFO] +- org.powermock:powermock-module-junit4:jar:1.6.1:compile
[INFO] +- org.jacoco:org.jacoco.agent:jar:0.7.9:compile
[INFO] +- org.springframework:spring-instrument-tomcat:jar:4.1.9.RELEASE:compile
[INFO] +- org.apache.tomcat:tomcat-catalina:jar:9.0.10:compile
[INFO] |  +- org.apache.tomcat:tomcat-annotations-api:jar:9.0.10:compile
[INFO] |  \- org.apache.tomcat:tomcat-jaspic-api:jar:9.0.10:compile
[INFO] +- com.liferay:com.liferay.ant.bnd:jar:3.0.3:compile
[INFO] +- sun-jaxb:jaxb-api:jar:2.1.9:compile
[INFO] +- net.jsourcerer.webdriver:JSErrorCollector:jar:0.6-atlassian-3:compile
[INFO] |  \- org.seleniumhq.selenium:selenium-firefox-driver:jar:2.51.0:compile
[INFO] |     \- org.seleniumhq.selenium:selenium-remote-driver:jar:2.51.0:compile
[INFO] |        \- net.java.dev.jna:jna-platform:jar:4.1.0:compile
[INFO] +- org.apache.tomcat:tomcat-util:jar:9.0.10:compile
[INFO] +- org.apache.velocity:velocity:jar:1.6.4:compile
[INFO] +- org.postgresql:postgresql:jar:42.0.0:compile
[INFO] +- p6spy:p6spy:jar:1.3:compile
[INFO] +- org.freemarker:freemarker:jar:2.3.23:compile
[INFO] +- org.springframework:spring-instrument:jar:4.1.9.RELEASE:compile
[INFO] +- com.liferay:com.caucho:jar:4.0.44:compile
[INFO] +- org.powermock:powermock-api-mockito:jar:1.6.1:compile
[INFO] +- org.apache.maven:maven-ant-tasks:jar:2.1.3:compile
[INFO] |  +- classworlds:classworlds:jar:1.1-alpha-2:compile
[INFO] |  +- org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9-stable-1:compile
[INFO] |  +- org.codehaus.plexus:plexus-utils:jar:1.5.15:compile
[INFO] |  +- org.codehaus.plexus:plexus-interpolation:jar:1.11:compile
[INFO] |  +- org.apache.maven:maven-artifact:jar:2.2.1:compile
[INFO] |  +- org.apache.maven:maven-artifact-manager:jar:2.2.1:compile
[INFO] |  |  \- org.apache.maven:maven-repository-metadata:jar:2.2.1:compile
[INFO] |  +- org.apache.maven:maven-model:jar:2.2.1:compile
[INFO] |  +- org.apache.maven:maven-project:jar:2.2.1:compile
[INFO] |  |  +- org.apache.maven:maven-profile:jar:2.2.1:compile
[INFO] |  |  \- org.apache.maven:maven-plugin-registry:jar:2.2.1:compile
[INFO] |  +- org.apache.maven:maven-error-diagnostics:jar:2.2.1:compile
[INFO] |  +- org.apache.maven:maven-settings:jar:2.2.1:compile
[INFO] |  +- org.apache.maven.wagon:wagon-file:jar:1.0-beta-6:compile
[INFO] |  +- org.apache.maven.wagon:wagon-http-lightweight:jar:1.0-beta-6:compile
[INFO] |  |  \- org.apache.maven.wagon:wagon-http-shared:jar:1.0-beta-6:compile
[INFO] |  |     +- nekohtml:xercesMinimal:jar:1.9.6.2:compile
[INFO] |  |     \- nekohtml:nekohtml:jar:1.9.6.2:compile
[INFO] |  \- org.apache.maven.wagon:wagon-provider-api:jar:1.0-beta-6:compile
[INFO] +- org.xmlresolver:xmlresolver:jar:0.12.5:compile
[INFO] |  +- org.apache.logging.log4j:log4j-api:jar:2.1:compile
[INFO] |  +- org.apache.logging.log4j:log4j-core:jar:2.1:compile
[INFO] |  \- org.apache.logging.log4j:log4j-slf4j-impl:jar:2.1:compile
[INFO] +- junit:junit:jar:4.12:compile
[INFO] +- org.eclipse.jetty:jetty-util:jar:8.1.10.v20130312:compile
[INFO] +- com.liferay.alloy-taglibs:alloy-taglib:jar:1.1.13:compile
[INFO] +- javax.enterprise.deploy:deployment-api:jar:1.2-rev-1:compile
[INFO] +- org.springframework:spring-context:jar:4.1.9.RELEASE:compile
[INFO] +- xml-apis:xml-apis:jar:1.4.01:compile
[INFO] +- com.liferay:nl.captcha.simplecaptcha:jar:1.1.1:compile
[INFO] +- org.springframework:spring-webmvc-portlet:jar:4.1.9.RELEASE:compile
[INFO] +- com.liferay:javax.xml.bind:jar:2.3.0.LIFERAY-PATCHED-1:compile
[INFO] +- odmg:odmg:jar:3.0:compile
[INFO] +- org.apache.chemistry.opencmis:chemistry-opencmis-client-impl:jar:0.13.0:compile
[INFO] +- org.apache.xbean:xbean-spring:jar:2.8:compile
[INFO] |  \- org.springframework:spring:jar:1.2.4:compile
[INFO] +- xalan:xalan:jar:2.7.2:compile
[INFO] +- com.zaxxer:HikariCP:jar:2.6.3:compile
[INFO] +- org.incava:java-diff:jar:1.1:compile
[INFO] +- com.redhat.qe:json-java:jar:20110202:compile
[INFO] +- org.apache.httpcomponents:httpmime:jar:4.5.5:compile
[INFO] +- com.liferay:net.jmge.gif.gif89:jar:1.0:compile
[INFO] +- org.aspectj:aspectjweaver:jar:1.8.13:compile
[INFO] +- org.jodd:jodd-servlet:jar:3.6.4:compile
[INFO] +- com.liferay:com.sun.syndication:jar:1.0.LIFERAY-PATCHED-1:compile
[INFO] +- org.antlr:stringtemplate:jar:3.0:compile
[INFO] +- org.apache.abdera:abdera-bundle:jar:1.1.3:compile
[INFO] |  +- org.apache.geronimo.specs:geronimo-activation_1.1_spec:jar:1.1:compile
[INFO] |  +- org.apache.geronimo.specs:geronimo-stax-api_1.0_spec:jar:1.0.1:compile
[INFO] |  +- org.apache.ws.commons.axiom:axiom-api:jar:1.2.14:compile
[INFO] |  +- org.apache.geronimo.specs:geronimo-javamail_1.4_spec:jar:1.7.1:compile
[INFO] |  +- org.apache.ws.commons.axiom:axiom-impl:jar:1.2.14:compile
[INFO] |  +- org.codehaus.woodstox:woodstox-core-asl:jar:4.1.4:compile
[INFO] |  +- org.codehaus.woodstox:stax2-api:jar:3.1.1:compile
[INFO] |  +- javax.servlet:servlet-api:jar:2.5:compile
[INFO] |  +- org.apache.jackrabbit:jackrabbit-core:jar:1.4:compile
[INFO] |  +- org.apache.jackrabbit:jackrabbit-api:jar:1.4:compile
[INFO] |  +- org.apache.jackrabbit:jackrabbit-jcr-commons:jar:1.4:compile
[INFO] |  +- org.apache.jackrabbit:jackrabbit-spi-commons:jar:1.4:compile
[INFO] |  +- org.apache.jackrabbit:jackrabbit-spi:jar:1.4:compile
[INFO] |  +- org.apache.jackrabbit:jackrabbit-text-extractors:jar:1.4:compile
[INFO] |  +- org.apache.lucene:lucene-core:jar:2.2.0:compile
[INFO] |  +- org.apache.derby:derby:jar:10.2.1.6:compile
[INFO] |  +- javax.jcr:jcr:jar:1.0:compile
[INFO] |  +- org.apache.ibatis:ibatis-sqlmap:jar:2.3.0:compile
[INFO] |  +- xml-security:xmlsec:jar:1.3.0:compile
[INFO] |  +- bouncycastle:bcprov-jdk15:jar:124:compile
[INFO] |  +- nu.validator.htmlparser:htmlparser:jar:1.0.5:compile
[INFO] |  +- net.sf.json-lib:json-lib:jar:jdk15:2.2.2:compile
[INFO] |  \- net.sf.ezmorph:ezmorph:jar:1.0.4:compile
[INFO] +- org.apache.tomcat:tomcat-jdbc:jar:9.0.10:compile
[INFO] +- com.liferay:org.apache.axis:jar:1.4.LIFERAY-PATCHED-2:compile
[INFO] +- commons-io:commons-io:jar:2.5:compile
[INFO] +- org.hibernate:hibernate-commons-annotations:jar:3.2.0.Final:compile
[INFO] +- commons-discovery:commons-discovery:jar:0.4:compile
[INFO] +- net.htmlparser.jericho:jericho-html:jar:3.1:compile
[INFO] +- com.liferay:org.apache.regexp:jar:1.5:compile
[INFO] +- commons-chain:commons-chain:jar:1.2:compile
[INFO] +- org.jodd:jodd-upload:jar:3.6.4:compile
[INFO] +- org.jodd:jodd-core:jar:3.6.8:compile
[INFO] +- com.adobe.xmp:xmpcore:jar:5.1.3:compile
[INFO] +- org.antlr:antlr-runtime:jar:3.0.1:compile
[INFO] +- org.ow2.asm:asm-debug-all:jar:5.0.4:compile
[INFO] +- org.springframework:spring-aop:jar:4.1.9.RELEASE:compile
[INFO] +- org.slf4j:slf4j-api:jar:1.7.2:compile
[INFO] +- edu.ucar:netcdf:jar:4.2.20:compile
[INFO] |  \- edu.ucar:unidataCommon:jar:4.2.20:compile
[INFO] |     \- net.jcip:jcip-annotations:jar:1.0:compile
[INFO] +- org.apache.pdfbox:fontbox:jar:2.0.9:compile
[INFO] +- org.apache.tika:tika-parsers:jar:1.18:compile
[INFO] |  +- com.healthmarketscience.jackcess:jackcess:jar:2.1.10:compile
[INFO] |  +- com.healthmarketscience.jackcess:jackcess-encrypt:jar:2.1.4:compile
[INFO] |  +- org.brotli:dec:jar:0.1.2:compile
[INFO] |  +- org.apache.pdfbox:pdfbox-tools:jar:2.0.9:compile
[INFO] |  +- org.bouncycastle:bcmail-jdk15on:jar:1.54:compile
[INFO] |  |  \- org.bouncycastle:bcpkix-jdk15on:jar:1.54:compile
[INFO] |  +- org.bouncycastle:bcprov-jdk15on:jar:1.54:compile
[INFO] |  +- org.ow2.asm:asm:jar:5.0.4:compile
[INFO] |  +- de.l3s.boilerpipe:boilerpipe:jar:1.1.0:compile
[INFO] |  +- org.codelibs:jhighlight:jar:1.0.2:compile
[INFO] |  +- com.github.junrar:junrar:jar:0.7:compile
[INFO] |  +- org.apache.cxf:cxf-rt-rs-client:jar:3.0.16:compile
[INFO] |  |  +- org.apache.cxf:cxf-rt-transports-http:jar:3.0.16:compile
[INFO] |  |  +- org.apache.cxf:cxf-core:jar:3.0.16:compile
[INFO] |  |  |  \- org.apache.ws.xmlschema:xmlschema-core:jar:2.2.2:compile
[INFO] |  |  \- org.apache.cxf:cxf-rt-frontend-jaxrs:jar:3.0.16:compile
[INFO] |  +- org.apache.opennlp:opennlp-tools:jar:1.8.4:compile
[INFO] |  +- com.googlecode.json-simple:json-simple:jar:1.1.1:compile
[INFO] |  +- com.github.openjson:openjson:jar:1.0.10:compile
[INFO] |  +- org.slf4j:jul-to-slf4j:jar:1.7.24:compile
[INFO] |  +- edu.ucar:netcdf4:jar:4.5.5:compile
[INFO] |  +- edu.ucar:grib:jar:4.5.5:compile
[INFO] |  |  \- org.itadaki:bzip2:jar:0.9.1:compile
[INFO] |  +- org.jsoup:jsoup:jar:1.11.2:compile
[INFO] |  +- edu.ucar:cdm:jar:4.5.5:compile
[INFO] |  |  +- edu.ucar:udunits:jar:4.5.5:compile
[INFO] |  |  +- org.quartz-scheduler:quartz:jar:2.2.0:compile
[INFO] |  |  |  \- c3p0:c3p0:jar:0.9.1.1:compile
[INFO] |  |  +- net.sf.ehcache:ehcache-core:jar:2.6.2:compile
[INFO] |  |  \- com.beust:jcommander:jar:1.35:compile
[INFO] |  +- edu.ucar:httpservices:jar:4.5.5:compile
[INFO] |  +- org.apache.commons:commons-csv:jar:1.0:compile
[INFO] |  +- org.apache.sis.core:sis-utility:jar:0.8:compile
[INFO] |  |  \- javax.measure:unit-api:jar:1.0:compile
[INFO] |  +- org.apache.sis.storage:sis-netcdf:jar:0.8:compile
[INFO] |  |  +- org.apache.sis.storage:sis-storage:jar:0.8:compile
[INFO] |  |  |  \- org.apache.sis.core:sis-feature:jar:0.8:compile
[INFO] |  |  \- org.apache.sis.core:sis-referencing:jar:0.8:compile
[INFO] |  +- org.apache.sis.core:sis-metadata:jar:0.8:compile
[INFO] |  +- org.opengis:geoapi:jar:3.0.1:compile
[INFO] |  +- edu.usc.ir:sentiment-analysis-parser:jar:0.1:compile
[INFO] |  +- org.apache.uima:uimafit-core:jar:2.2.0:compile
[INFO] |  |  \- commons-logging:commons-logging-api:jar:1.1:compile
[INFO] |  +- org.apache.uima:uimaj-core:jar:2.9.0:compile
[INFO] |  +- org.jdom:jdom2:jar:2.0.6:compile
[INFO] |  +- com.fasterxml.jackson.core:jackson-core:jar:2.9.5:compile
[INFO] |  +- com.fasterxml.jackson.core:jackson-databind:jar:2.9.5:compile
[INFO] |  +- com.fasterxml.jackson.core:jackson-annotations:jar:2.9.5:compile
[INFO] |  +- org.apache.pdfbox:jbig2-imageio:jar:3.0.0:compile
[INFO] |  \- com.github.jai-imageio:jai-imageio-core:jar:1.3.1:compile
[INFO] +- com.liferay:org.apache.commons.jrcs.diff:jar:0.3.0:compile
[INFO] +- org.apache.poi:poi-scratchpad:jar:3.15:compile
[INFO] +- soap:soap:jar:2.2:compile
[INFO] +- ecs:ecs:jar:1.4.2:compile
[INFO] +- org.bouncycastle:bcprov-jdk16:jar:1.45:compile
[INFO] +- commons-httpclient:commons-httpclient:jar:3.1:compile
[INFO] +- com.liferay:javax.xml.ws:jar:2.3.0.LIFERAY-PATCHED-1:compile
[INFO] +- org.apache.axis:axis-ant:jar:1.4:compile
[INFO] +- org.openoffice:juh:jar:2.3.1:compile
[INFO] +- com.pff:java-libpst:jar:0.8.1:compile
[INFO] +- com.mchange:c3p0:jar:0.9.5.2:compile
[INFO] +- com.thoughtworks.xstream:xstream:jar:1.4.10:compile
[INFO] |  \- xmlpull:xmlpull:jar:1.1.3.1:compile
[INFO] +- org.springframework:spring-tx:jar:4.1.9.RELEASE:compile
[INFO] +- org.springframework:spring-oxm:jar:4.1.9.RELEASE:compile
[INFO] +- com.liferay:com.hp.hpl.jena:jar:1.4:compile
[INFO] +- org.springframework:spring-expression:jar:4.1.9.RELEASE:compile
[INFO] +- org.apache.ant:ant:jar:1.8.4:compile
[INFO] |  \- org.apache.ant:ant-launcher:jar:1.8.4:compile
[INFO] +- org.eclipse.core:runtime:jar:20070801:compile
[INFO] +- org.apache.commons:commons-exec:jar:1.3:compile
[INFO] +- com.sun:jai_core:jar:1.1.3:compile
[INFO] +- com.liferay:com.ibm.icu4j:jar:54.1.1.LIFERAY-PATCHED-2:compile
[INFO] +- org.jodd:jodd-bean:jar:3.6.4:compile
[INFO] +- com.liferay:de.l3s.boilerpipe:jar:1.1.0.LIFERAY-PATCHED-1:compile
[INFO] +- wsdl4j:wsdl4j:jar:1.6.3:compile
[INFO] +- commons-validator:commons-validator:jar:1.5.1:compile
[INFO] +- com.google.javascript:closure-compiler:jar:v20131014:compile
[INFO] |  +- args4j:args4j:jar:2.0.16:compile
[INFO] |  +- com.google.protobuf:protobuf-java:jar:2.4.1:compile
[INFO] |  \- com.google.code.findbugs:jsr305:jar:1.3.9:compile
[INFO] +- net.sourceforge.nekohtml:nekohtml:jar:1.9.22:compile
[INFO] +- org.apache.httpcomponents:httpcore:jar:4.4.9:compile
[INFO] +- net.sf.kxml:kxml2:jar:2.3.0:compile
[INFO] +- jfree:jfreechart:jar:1.0.13:compile
[INFO] +- com.googlecode.mp4parser:isoparser:jar:1.1.22:compile
[INFO] +- com.sun.xml.bind:jaxb-impl:jar:2.1.17:compile
[INFO] |  +- com.sun.xml.bind:jaxb-xjc:jar:2.1.17:compile
[INFO] |  \- com.sun.xml.fastinfoset:FastInfoset:jar:1.2.12:compile
[INFO] |     \- javax.xml.bind:jsr173_api:jar:1.0:compile
[INFO] +- xerces:xercesImpl:jar:2.11.0:compile
[INFO] +- org.javassist:javassist:jar:3.18.2-GA:compile
[INFO] +- easyconf:easyconf:jar:0.9.5:compile
[INFO] |  +- struts:struts:jar:1.1:compile
[INFO] |  |  +- struts:struts-legacy:jar:1.1:compile
[INFO] |  |  \- javax.sql:jdbc-stdext:jar:2.0:compile
[INFO] |  +- commons-beanutils:commons-beanutils-core:jar:1.7.0:compile
[INFO] |  +- commons-beanutils:commons-beanutils-bean-collections:jar:1.7.0:compile
[INFO] |  +- mx4j:mx4j-jmx:jar:2.1.1:compile
[INFO] |  +- mx4j:mx4j-impl:jar:2.1.1:compile
[INFO] |  \- xstream:xstream:jar:1.1.2:compile
[INFO] +- org.gagravarr:vorbis-java-core:jar:0.8:compile
[INFO] +- org.tuckey:urlrewritefilter:jar:4.0.4:compile
[INFO] +- com.liferay:com.megginson.sax.rdf:jar:1.0:compile
[INFO] +- org.apache.chemistry.opencmis:chemistry-opencmis-client-api:jar:0.13.0:compile
[INFO] +- commons-digester:commons-digester:jar:1.8.1:compile
[INFO] +- org.jvnet.staxex:stax-ex:jar:1.2:compile
[INFO] |  \- javax.xml.stream:stax-api:jar:1.0:compile
[INFO] +- com.liferay:org.mozilla.intl.chardet:jar:1.1:compile
[INFO] +- com.sun.xml.stream.buffer:streambuffer:jar:0.9:compile
[INFO] +- org.slf4j:jcl-over-slf4j:jar:1.7.2:compile
[INFO] +- commons-dbcp:commons-dbcp:jar:1.2.2:compile
[INFO] +- bsf:bsf:jar:2.4.0:compile
[INFO] +- commons-codec:commons-codec:jar:1.9:compile
[INFO] +- org.codehaus.woodstox:wstx-asl:jar:3.2.8:compile
[INFO] +- org.apache.struts:struts-core:jar:1.3.10:compile
[INFO] +- org.springframework:spring-aspects:jar:4.1.9.RELEASE:compile
[INFO] +- com.liferay:javax.xml.soap:jar:1.4.0.LIFERAY-PATCHED-1:compile
[INFO] +- com.liferay:javax.ccpp.ccpp-ri:jar:1.0:compile
[INFO] +- commons-fileupload:commons-fileupload:jar:1.3.3:compile
[INFO] +- org.samba.jcifs:jcifs:jar:1.3.14-kohsuke-1:compile
[INFO] +- org.openoffice:unoil:jar:2.3.1:compile
[INFO] +- commons-pool:commons-pool:jar:1.5.7:compile
[INFO] +- org.jodd:jodd-http:jar:3.6.4:compile
[INFO] +- com.sun.xml.ws:jaxws-rt:jar:2.1.7:compile
[INFO] |  +- javax.xml.ws:jaxws-api:jar:2.1:compile
[INFO] |  |  \- javax.xml.bind:jaxb-api:jar:2.1:compile
[INFO] |  \- com.sun.org.apache.xml.internal:resolver:jar:20050927:compile
[INFO] +- javax.xml.soap:saaj-api:jar:1.3:compile
[INFO] +- com.liferay:com.coucho.hessian:jar:4.0.3:compile
[INFO] +- org.glassfish.web:jstl-impl:jar:1.2:compile
[INFO] +- jaxen:jaxen:jar:1.1.6:compile
[INFO] +- com.mchange:mchange-commons-java:jar:0.2.15:compile
[INFO] +- org.springframework:spring-webmvc:jar:4.1.9.RELEASE:compile
[INFO] +- org.springframework:spring-core:jar:4.1.9.RELEASE:compile
[INFO] +- org.apache.pdfbox:pdfbox:jar:2.0.9:compile
[INFO] +- org.apache.chemistry.opencmis:chemistry-opencmis-client-bindings:jar:0.13.0:compile
[INFO] +- com.liferay:org.outerj.daisy.daisydiff:jar:1.2:compile
[INFO] +- net.sf.jsr107cache:jsr107cache:jar:1.0:compile
[INFO] +- com.sun.media:jai-codec:jar:1.1.3:compile
[INFO] |  \- javax.media:jai-core:jar:1.1.3:compile
[INFO] +- com.liferay:javax.xml.rpc:jar:1.1:compile
[INFO] +- org.apache.chemistry.opencmis:chemistry-opencmis-commons-impl:jar:0.13.0:compile
[INFO] +- org.apache.santuario:xmlsec:jar:1.5.8:compile
[INFO] +- log4j:apache-log4j-extras:jar:1.2.17:compile
[INFO] +- org.freshcookies:freshcookies-security:jar:0.60:compile
[INFO] +- org.apache.commons:commons-math:jar:2.0:compile
[INFO] +- org.apache.james:apache-mime4j-core:jar:0.7.2:compile
[INFO] +- org.apache.tomcat:tomcat-juli:jar:9.0.10:compile
[INFO] +- org.apache.james:apache-mime4j-dom:jar:0.7.2:compile
[INFO] +- jfree:jcommon:jar:1.0.16:compile
[INFO] +- com.uwyn:jhighlight:jar:1.0:compile
[INFO] +- org.jodd:jodd-proxetta:jar:3.6.4:compile
[INFO] |  \- org.jodd:jodd-log:jar:3.6.4:compile
[INFO] +- org.htmlparser:htmlparser:jar:1.6:compile
[INFO] +- com.liferay:org.monte:jar:0.7.7:compile
[INFO] +- com.liferay:xuggle.xuggler.noarch:jar:5.4:compile
[INFO] +- log4j:log4j:jar:1.2.17:compile
[INFO] +- org.apache.httpcomponents:httpclient:jar:4.5.5:compile
[INFO] +- net.fortuna.ical4j:ical4j:jar:1.0-rc3:compile
[INFO] |  \- backport-util-concurrent:backport-util-concurrent:jar:3.1:compile
[INFO] +- cglib:cglib-nodep:jar:2.2.2:compile
[INFO] +- org.springframework:spring-context-support:jar:4.1.9.RELEASE:compile
[INFO] +- javax.ccpp:ccpp:jar:1.0:compile
[INFO] +- aopalliance:aopalliance:jar:1.0:compile
[INFO] +- org.apache.tika:tika-core:jar:1.18:compile
[INFO] +- stax:stax-api:jar:1.0.1:compile
[INFO] +- org.jvnet:mimepull:jar:1.3:compile
[INFO] +- org.apache.poi:poi-ooxml:jar:3.15:compile
[INFO] |  \- com.github.virtuald:curvesapi:jar:1.04:compile
[INFO] +- org.apache.poi:poi:jar:3.15:compile
[INFO] |  \- org.apache.commons:commons-collections4:jar:4.1:compile
[INFO] +- javax.servlet.jsp.jstl:jstl-api:jar:1.2:compile
[INFO] +- displaytag:displaytag:jar:1.2:compile
[INFO] |  +- com.lowagie:itext:jar:1.3:compile
[INFO] |  +- org.slf4j:jcl104-over-slf4j:jar:1.4.2:compile
[INFO] |  \- org.slf4j:slf4j-log4j12:jar:1.4.2:compile
[INFO] +- org.hyperic:sigar:jar:1.6.4:compile
[INFO] +- org.mozilla:rhino:jar:1.7R4:compile
[INFO] +- truezip:truezip:jar:6.7:compile
[INFO] +- org.tallison:jmatio:jar:1.2:compile
[INFO] +- io.netty:netty-all:jar:4.0.23.Final:compile
[INFO] +- org.antlr:antlr:jar:3.0.1:compile
[INFO] +- antlr:antlr:jar:2.7.7:compile
[INFO] +- com.drewnoakes:metadata-extractor:jar:2.9.1:compile
[INFO] +- org.scribe:scribe:jar:1.0.9:compile
[INFO] +- xpp3:xpp3_min:jar:1.1.4c:compile
[INFO] +- org.bouncycastle:bcmail-jdk16:jar:1.45:compile
[INFO] +- org.jopendocument:jdom:jar:1.1.1:compile
[INFO] +- org.springframework:spring-jms:jar:4.1.9.RELEASE:compile
[INFO] |  \- org.springframework:spring-messaging:jar:4.1.9.RELEASE:compile
[INFO] +- commons-beanutils:commons-beanutils:jar:1.9.2:compile
[INFO] +- org.gagravarr:vorbis-java-tika:jar:0.8:compile
[INFO] +- com.liferay:org.vps.crypt:jar:1.0:compile
[INFO] +- com.liferay:com.artofsolving.jodconverter:jar:2.2.2:compile
[INFO] +- com.googlecode.juniversalchardet:juniversalchardet:jar:1.0.3:compile
[INFO] +- net.sf.jazzy:jazzy:jar:0.5.2-rtext-1.4.1-2:compile
[INFO] +- com.jhlabs:imaging:jar:01012005:compile
[INFO] +- org.aspectj:aspectjrt:jar:1.8.13:compile
[INFO] +- commons-logging:commons-logging:jar:1.2:compile
[INFO] +- com.liferay:org.apache.xmlbeans:jar:2.5.0.LIFERAY-PATCHED-1:compile
[INFO] +- com.liferay:com.github.fge.json.schema.validator:jar:2.2.3.LIFERAY-PATCHED-2:compile
[INFO] +- commons-configuration:commons-configuration:jar:1.10:compile
[INFO] +- org.apache.commons:commons-compress:jar:1.18:compile
[INFO] +- com.liferay:javax.jws:jar:1.1.0.LIFERAY-PATCHED-1:compile
[INFO] +- org.springframework:spring-orm:jar:4.1.9.RELEASE:compile
[INFO] +- org.openoffice:ridl:jar:2.3.1:compile
[INFO] +- com.liferay:org.jabsorb:jar:1.3.2.LIFERAY-PATCHED-1:compile
[INFO] +- org.openoffice:jurt:jar:2.3.1:compile
[INFO] +- org.im4java:im4java:jar:1.2.0:compile
[INFO] +- dom4j:dom4j:jar:1.6.1:compile
[INFO] +- net.java.dev.jna:jna:jar:4.1.0:compile
[INFO] +- org.springframework:spring-web:jar:4.1.9.RELEASE:compile
[INFO] +- org.apache.chemistry.opencmis:chemistry-opencmis-commons-api:jar:0.13.0:compile
[INFO] +- com.rometools:rome:jar:1.5.1:compile
[INFO] |  +- com.rometools:rome-utils:jar:1.5.1:compile
[INFO] |  \- org.jdom:jdom:jar:2.0.2:compile
[INFO] +- com.liferay:org.hibernate.core:jar:3.6.10.LIFERAY-PATCHED-3:compile
[INFO] +- commons-lang:commons-lang:jar:2.6:compile
[INFO] +- org.jodd:jodd-json:jar:3.6.4:compile
[INFO] +- concurrent:concurrent:jar:1.3.4:compile
[INFO] +- org.springframework:spring-beans:jar:4.1.9.RELEASE:compile
[INFO] +- javax.transaction:javax.transaction-api:jar:1.3:compile
[INFO] +- commons-collections:commons-collections:jar:3.2.2:compile
[INFO] +- org.jboss.spec.javax.rmi:jboss-rmi-api_1.0_spec:jar:1.0.5.Final:compile
[INFO] +- org.glassfish.jersey.core:jersey-common:jar:2.26:compile
[INFO] |  +- javax.annotation:javax.annotation-api:jar:1.2:compile
[INFO] |  +- org.glassfish.hk2.external:javax.inject:jar:2.5.0-b42:compile
[INFO] |  \- org.glassfish.hk2:osgi-resource-locator:jar:1.0.1:compile
[INFO] +- org.apache.pdfbox:jempbox:jar:1.8.14:compile
[INFO] +- org.ccil.cowan.tagsoup:tagsoup:jar:1.2.1:compile
[INFO] +- org.tukaani:xz:jar:1.5:compile
[INFO] +- oro:oro:jar:2.0.8:compile
[INFO] +- xalan:serializer:jar:2.7.2:compile
[INFO] +- org.apache.poi:poi-ooxml-schemas:jar:3.15:compile
[INFO] |  \- org.apache.xmlbeans:xmlbeans:jar:2.6.0:compile
[INFO] +- org.springframework:spring-jdbc:jar:4.1.9.RELEASE:compile
[INFO] +- com.sun.xml.messaging.saaj:saaj-impl:jar:1.3:compile
[INFO] \- com.yahoo.platform.yui:yuicompressor:jar:2.4.8:compile
[INFO]    \- rhino:js:jar:1.7R2:compile
```

## License
LGPL-2.1

[1]: https://www.jetbrains.com/help/idea/structural-search-and-replace.html
[2]: https://www.jetbrains.com/help/idea/navigating-through-the-source-code.html#go_to_implementation
