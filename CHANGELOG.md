### 2.21.0 (08.11.2021)

- Upgrade `garpix_menu` to version 1.6.2.

### 2.20.0 (08.11.2021)

- Upgrade `garpix_menu` to version 1.6.1.

### 2.19.0 (08.11.2021)

- Add social urls.

### 2.19.0 (18.10.2021)

- Upgrade `garpix_menu` to version 1.6.0.

### 2.18.0 (18.10.2021)

- Upgrade `garpix_auth` to version 2.3.0.

### 2.17.0 (08.10.2021)

- Upgrade `garpix_auth` to version 2.2.0.

### 2.16.0 (26.09.2021)

- Upgrade `garpix_page` to version 2.12.0.

### 2.15.0 (25.09.2021)

- Upgrade `garpix_page` to version 2.11.0.

### 2.14.0 (21.09.2021)

- Upgrade `garpix_auth` to version 2.1.0.

### 2.13.0 (19.09.2021)

- Upgrade `garpix_menu` to version 1.5.1.

### 2.12.0 (19.09.2021)

- Upgrade `garpix_menu` to version 1.5.0.

### 2.11.0 (19.09.2021)

- Upgrade `garpix_menu` to version 1.4.0.

### 2.10.0 (19.09.2021)

- Added global context for api pages.
- Upgrade `garpix_menu` to version 1.3.0.

### 2.9.0 (19.09.2021)

- Added endpoint `{API_URL}/page/{page_slug}` for SPA sites.

### 2.8.1 (18.09.2021)

- Added to INSTALLED_APPS 'django.contrib.sitemaps'.

### 2.8.0 (18.09.2021)

- Upgrade `garpix_menu` to version 1.2.0.

### 2.7.0 (15.09.2021)

- Added settings.py variable `API_URL` (defaults to `api`).

### 2.6.0 (14.09.2021)

- Upgrade `garpix_page` to version 2.9.0.
- Upgrade `garpix_qa` to version 1.2.0.

### 2.5.0 (10.09.2021)

- Upgrade `garpix_auth` to version 2.0.2.

### 2.4.0 (10.09.2021)

- Upgrade `garpix_page` to version 2.8.0.

### 2.3.0 (09.09.2021)

- Upgrade `garpix_page` to version 2.7.0.

### 2.2.1 (08.09.2021)

- Hotfix: Added `garpix_utils` to INSTALLED_APPS.

### 2.2.0 (08.09.2021)

- Upgrade `garpix_utils` to version 1.3.0.
- Upgrade `garpix_page` to version 2.6.0.
- Upgrade `garpix_menu` to version 1.1.0.
- Changed `drf_yasg` to `drf_spectacular`.

### 2.1.0 (02.09.2021)

- Upgrade `garpix_notify` to version 4.1.0.

### 2.0.4 (02.09.2021)

- Upgrade `garpix_notify` to version 4.0.2.

### 2.0.3 (27.08.2021)

- Upgrade `garpix_notify` to version 4.0.1.

### 2.0.1-2.0.2 (19.08.2021)

- Hot fixes.

### 2.0.0 (19.08.2021)

- Upgrade `garpix_auth` to version 2.0.1.

### 1.15.0 (12.08.2021)

- Upgrade `garpix_notify` to version 4.0.0.

### 1.14.0 (08.08.2021)

- Upgrade `garpix_pack` to `garpix_package` version 2.0.0.

### 1.13.0 (06.08.2021)

- Upgrade `garpix_page` to version 2.5.0.

### 1.12.0 (29.07.2021)

- Upgrade `garpix_page` to version 2.4.0.

### 1.11.0 (29.07.2021)

- Upgrade `garpix_page` to version 2.3.0.

### 1.10.0 (29.07.2021)

- Added static urls to urlpatterns.

### 1.9.2 (27.07.2021)

- Upgrade `garpix_utils` to version 1.1.0.

### 1.9.1 (21.07.2021)

- Upgrade `garpix_utils` to version 1.0.2.

### 1.9.0 (21.07.2021)

- Added package `garpix_utils`.

### 1.8.1 (20.07.2021)

- Upgrade `garpix_menu` to version 1.0.2.

### 1.8.0 (19.07.2021)

- Url for login `token-auth/` changed to `api/login/`.

### 1.7.3 (19.07.2021)

- `ENABLE_GARPIX_AUTH` now is bool environment variable. Fixed bug with `reverse url authorize`.

### 1.7.2 (19.07.2021)

- Added `/frontend/templates` to `TEMPLATES` variable. 

### 1.7.1 (18.07.2021)

- From version 1.7.0 `pack` and `startpackage` into package `garpix_pack`.

### 1.7.0 (18.07.2021)

- Added manage.py command `pack` for packing packages. Syntax use - `python3 manage.py pack <app_name>`

### 1.6.4 (17.07.2021)

- Upgrade `garpix_menu` to version 1.0.1.

### 1.6.3 (12.07.2021)

- Upgrade `garpix_notify` to version 3.0.3.

### 1.6.2 (11.07.2021)

- Path for `.env` file.

### 1.6.1 (08.07.2021)

- Resort `INSTALLED_APPS`.

### 1.6.0 (08.07.2021)

- Added `django-cors-headers`. If `DEBUG == True`, then `CORS_ALLOW_ALL_ORIGINS = True`

### 1.5.2 (03.07.2021)

- Upgrade `garpix_qa` to version 1.0.6.

### 1.5.1 (01.07.2021)

- Changed `/static/` to `/static-backend/`.

### 1.5.0 (01.07.2021)

- Upgrade `garpix_notify` to version 3.0.2.

### 1.4.3 (01.07.2021)

- Added documentation to url: `/api/docs/`

### 1.4.2 (29.06.2021)

- Bug fix with `BASE_DIR` for `garpix_qa`.

### 1.4.1 (28.06.2021)

- Bug fix with `garpix_notify` - url not resolved `authorize`.

### 1.4.0 (28.06.2021)

- Added `garpix_notify`.

### 1.3.1 (24.06.2021)

- Fix templates, docs.

### 1.3.0 (24.06.2021)

- Added `garpix_auth`.

### 1.2.0 (23.06.2021)

- Upgrade `garpix_page` to version 2.2.0.

### 1.1.0 (22.06.2021)

- Upgrade `garpix_page` to version 2.0.0.

### 1.0.3 (12.05.2021)

- Bug fix with djangorestframework dependency.

### 1.0.2 (12.05.2021)

- Bug fix with CKEditor dependency.

### 1.0.0-1.0.1 (11.05.2021)

- Release on pypi.org.
