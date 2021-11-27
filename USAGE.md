# Ready-to-use Ansible Host Docker Image

## 🤩 Usage 🤩

**... as local Copy**

```bash
docker pull tbcp/ansible
```

**... as Base Image**

```dockerfile
FROM tbcp/ansible

USER bootcamp
```

**... as GitLab-CI Image**

```yml
image: "tbcp/ansible"
```
