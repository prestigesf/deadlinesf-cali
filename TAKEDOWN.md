# deadlinesfcali takedown (run only at free-plan launch)

Restore point (prior production deploy): 6adec6d26befff51eaa5b8c2
Published 2026-10-25 8:19 PM PT. Content = main 4834b8b:live-snapshot-2026-10-19/index.html (md5 f633a890de30db16446f28098cbbb936).

Take offline (from repo root, branch retire-offline-2026-11-15):
    netlify deploy --prod --dir offline --site 6ced0b75-2633-4270-b770-74ba083725bf --message "Retired: moved to deadlinesf.net/free"
    netlify api lockDeploy --data '{"deploy_id":"<new deploy id>"}'

Undo: Netlify > deadlinesfcali > Deploys > 6adec6d26befff51eaa5b8c2 > Publish deploy, or
    netlify api restoreSiteDeploy --data '{"site_id":"6ced0b75-2633-4270-b770-74ba083725bf","deploy_id":"6adec6d26befff51eaa5b8c2"}'
