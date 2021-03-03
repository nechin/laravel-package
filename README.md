# Laravel helpers for a facades

Method *fileExt* to the __Str__ facade, that return a file extension by the file path
\Illuminate\Support\Str::fileExt('path\to\file.ext')

Method *redirectMap* to the __Route__ facade, that adds the ability to specify a list of redirects

\Illuminate\Routing\Route::redirectMap([
    '/from' => '/to'
]);
